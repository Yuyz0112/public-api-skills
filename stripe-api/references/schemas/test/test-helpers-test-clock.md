# test_helpers.test_clock

A test clock enables deterministic control over objects in testmode. With a test clock, you can create
objects at a frozen time in the past or future, and advance to a specific future time to observe webhooks and state changes. After the clock advances,
you can either validate the current state of your scenario (and test your assumptions), change the current state of your scenario (and test more complex scenarios), or keep advancing forward in time.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `deletes_after` | integer (unix-time) | Yes | Time at which this clock is scheduled to auto delete. |
| `frozen_time` | integer (unix-time) | Yes | Time at which all objects belonging to this clock are frozen. |
| `id` | string | Yes | Unique identifier for the object. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `name` | string | No | The custom name supplied at creation. |
| `object` | enum: test_helpers.test_clock | Yes | String representing the object's type. Objects of the same type share the same value. |
| `status` | enum: advancing, internal_failure, ready | Yes | The status of the Test Clock. |
| `status_details` | [billing_clocks_resource_status_details_status_details](billing-clocks-resource-status-details-status-details.md) | Yes |  |


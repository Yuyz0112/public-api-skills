# radar.value_list_item

Value list items allow you to add specific values to a given Radar value list, which can then be used in rules.

Related guide: [Managing list items](https://docs.stripe.com/radar/lists#managing-list-items)

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `created_by` | string | Yes | The name or email address of the user who added this item to the value list. |
| `id` | string | Yes | Unique identifier for the object. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `object` | enum: radar.value_list_item | Yes | String representing the object's type. Objects of the same type share the same value. |
| `value` | string | Yes | The value of the item. |
| `value_list` | string | Yes | The identifier of the value list this item belongs to. |


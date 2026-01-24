# webhook_endpoint

You can configure [webhook endpoints](https://docs.stripe.com/webhooks/) via the API to be
notified about events that happen in your Stripe account or connected
accounts.

Most users configure webhooks from [the dashboard](https://dashboard.stripe.com/webhooks), which provides a user interface for registering and testing your webhook endpoints.

Related guide: [Setting up webhooks](https://docs.stripe.com/webhooks/configure)

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `api_version` | string | No | The API version events are rendered as for this webhook endpoint. |
| `application` | string | No | The ID of the associated Connect application. |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `description` | string | No | An optional description of what the webhook is used for. |
| `enabled_events` | string[] | Yes | The list of events to enable for this endpoint. `['*']` indicates that all events are enabled, except those that require explicit selection. |
| `id` | string | Yes | Unique identifier for the object. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `metadata` | object | Yes | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `object` | enum: webhook_endpoint | Yes | String representing the object's type. Objects of the same type share the same value. |
| `secret` | string | No | The endpoint's secret, used to generate [webhook signatures](https://docs.stripe.com/webhooks/signatures). Only returned at creation. |
| `status` | string | Yes | The status of the webhook. It can be `enabled` or `disabled`. |
| `url` | string | Yes | The URL of the webhook endpoint. |


# WebhookCompact

Webhook objects represent the state of an active subscription for a server to be updated with information from Asana. This schema represents the subscription itself, not the objects that are sent to the server. For information on those please refer to the [event](/reference/events) schema.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `gid` | string | No | Globally unique identifier of the resource, as a string. |
| `resource_type` | string | No | The base type of this resource. |
| `active` | boolean | No | If true, the webhook will send events - if false it is considered inactive and will not generate events. |
| `resource` | [AsanaNamedResource](AsanaNamedResource.md) | No |  |
| `target` | string (uri) | No | The URL to receive the HTTP POST. |


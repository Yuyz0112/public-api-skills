# WebhookFilter

A WebhookFilter can be passed on creation of a webhook in order to filter the types of actions that trigger delivery of an [event](/reference/events)

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `resource_type` | string | No | The type of the resource which created the event when modified; for example, to filter to changes on regular tasks this field should be set to `task`. |
| `resource_subtype` | string | No | The resource subtype of the resource that the filter applies to. This should be set to the same value as is returned on the `resource_subtype` field on the resources themselves. |
| `action` | string | No | The type of change on the **resource** to pass through the filter. For more information refer to `Event.action` in the [event](/reference/events) schema. This can be one of `changed`, `added`, `removed`, `deleted`, and `undeleted` depending on the nature of what has occurred on the resource. |
| `fields` | string[] | No | *Conditional.* A whitelist of fields for events which will pass the filter when the resource is changed. These can be any combination of the fields on the resources themselves. This field is only valid for `action` of type `changed`
*Note: Subscriptions created on higher-level resources such as a Workspace, Team, or Portfolio do not support fields.* |


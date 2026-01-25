# AttachmentRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `resource_subtype` | enum: asana, external | No | The type of the attachment. Must be one of the given values. If not specified, a file attachment of type `asana` will be assumed. Note that if the value of `resource_subtype` is `external`, a `parent`, `name`, and `url` must also be provided.
 |
| `file` | string (binary) | No | Required for `asana` attachments.
 |
| `parent` | string | Yes | Required identifier of the parent task, project, or project_brief, as a string.
 |
| `url` | string | No | The URL of the external resource being attached. Required for attachments of type `external`.
 |
| `name` | string | No | The name of the external resource being attached. Required for attachments of type `external`.
 |
| `connect_to_app` | boolean | No | *Optional*. Only relevant for external attachments with a parent task.
A boolean indicating whether the current app should be connected with
the attachment for the purposes of showing an app components widget.
Requires the app to have been added to a project the parent task is in.
This property can only be set if an OAuth token is used to authenticate the request.

Criteria for displaying app widget:
1. An OAuth token must be used to authenticate the request
2. The app needs to have its `widget_metadata_url` configured in the developer console
3. The task the attachment is being attached to must be in a project with the app installed |


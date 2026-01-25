# AttachmentCompact

An *attachment* object represents any file attached to a task in Asana, whether it's an uploaded file or one associated via a third-party service such as Dropbox or Google Drive.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `gid` | string | No | Globally unique identifier of the resource, as a string. |
| `resource_type` | string | No | The base type of this resource. |
| `name` | string | No | The name of the file. |
| `resource_subtype` | string | No | The service hosting the attachment. Valid values are `asana`, `dropbox`, `gdrive`, `onedrive`, `box`, `vimeo`, and `external`. |


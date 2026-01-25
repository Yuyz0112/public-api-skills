# Version

A version of a file

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | Unique identifier for version |
| `created_at` | string (date-time) | Yes | The UTC ISO 8601 time at which the version was created |
| `label` | string,null | Yes | The label given to the version in the editor |
| `description` | string,null | Yes | The description of the version as entered in the editor |
| `user` | [User](User.md) | Yes |  |
| `thumbnail_url` | string | No | A URL to a thumbnail image of the file version. |


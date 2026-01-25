# PublishedComponentSet

A node containing a set of variants of a component.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `key` | string | Yes | The unique identifier for the component set. |
| `file_key` | string | Yes | The unique identifier of the Figma file that contains the component set. |
| `node_id` | string | Yes | The unique identifier of the component set node within the Figma file. |
| `thumbnail_url` | string | No | A URL to a thumbnail image of the component set. |
| `name` | string | Yes | The name of the component set. |
| `description` | string | Yes | The description of the component set as entered by the publisher. |
| `created_at` | string (date-time) | Yes | The UTC ISO 8601 time when the component set was created. |
| `updated_at` | string (date-time) | Yes | The UTC ISO 8601 time when the component set was last updated. |
| `user` | [User](User.md) | Yes |  |
| `containing_frame` | [FrameInfo](FrameInfo.md) | No |  |


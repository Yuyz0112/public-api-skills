# PublishedComponent

An arrangement of published UI elements that can be instantiated across figma files.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `key` | string | Yes | The unique identifier for the component. |
| `file_key` | string | Yes | The unique identifier of the Figma file that contains the component. |
| `node_id` | string | Yes | The unique identifier of the component node within the Figma file. |
| `thumbnail_url` | string | No | A URL to a thumbnail image of the component. |
| `name` | string | Yes | The name of the component. |
| `description` | string | Yes | The description of the component as entered by the publisher. |
| `created_at` | string (date-time) | Yes | The UTC ISO 8601 time when the component was created. |
| `updated_at` | string (date-time) | Yes | The UTC ISO 8601 time when the component was last updated. |
| `user` | [User](User.md) | Yes |  |
| `containing_frame` | [FrameInfo](FrameInfo.md) | No |  |


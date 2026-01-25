# PublishedStyle

A set of published properties that can be applied to nodes.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `key` | string | Yes | The unique identifier for the style |
| `file_key` | string | Yes | The unique identifier of the Figma file that contains the style. |
| `node_id` | string | Yes | ID of the style node within the figma file |
| `style_type` | [StyleType](StyleType.md) | Yes |  |
| `thumbnail_url` | string | No | A URL to a thumbnail image of the style. |
| `name` | string | Yes | The name of the style. |
| `description` | string | Yes | The description of the style as entered by the publisher. |
| `created_at` | string (date-time) | Yes | The UTC ISO 8601 time when the style was created. |
| `updated_at` | string (date-time) | Yes | The UTC ISO 8601 time when the style was last updated. |
| `user` | [User](User.md) | Yes |  |
| `sort_position` | string | Yes | A user specified order number by which the style can be sorted. |


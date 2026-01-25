# Comment

A comment or reply left by a user.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | Unique identifier for comment. |
| `client_meta` | any | Yes | Positioning information of the comment. Includes information on the location of the comment pin, which is either the absolute coordinates on the canvas or a relative offset within a frame. If the comment is a region, it will also contain the region height, width, and position of the anchor in regards to the region. |
| `file_key` | string | Yes | The file in which the comment lives |
| `parent_id` | string | No | If present, the id of the comment to which this is the reply |
| `user` | [User](User.md) | Yes |  |
| `created_at` | string (date-time) | Yes | The UTC ISO 8601 time at which the comment was left |
| `resolved_at` | string,null (date-time) | No | If set, the UTC ISO 8601 time the comment was resolved |
| `message` | string | Yes | The content of the comment |
| `order_id` | string,null | Yes | Only set for top level comments. The number displayed with the comment in the UI |
| `reactions` | Reaction[] | Yes | An array of reactions to the comment |


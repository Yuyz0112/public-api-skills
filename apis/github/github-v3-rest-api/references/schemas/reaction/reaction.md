# reaction

Reactions to conversations provide a way to help people express their feelings more simply and effectively.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | Yes |  |
| `node_id` | string | Yes |  |
| `user` | [nullable-simple-user](nullable-simple-user.md) | Yes |  |
| `content` | enum: +1, -1, laugh... | Yes | The reaction to use |
| `created_at` | string (date-time) | Yes |  |


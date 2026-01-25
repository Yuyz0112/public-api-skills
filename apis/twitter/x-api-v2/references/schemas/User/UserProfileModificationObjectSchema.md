# UserProfileModificationObjectSchema

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `event_at` | string (date-time) | Yes | Event time. |
| `new_value` | string | Yes |  |
| `profile_field` | string | Yes |  |
| `user` | object | Yes |  |

## Nested Fields

### `user`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | [UserId](UserId.md) | Yes |  |


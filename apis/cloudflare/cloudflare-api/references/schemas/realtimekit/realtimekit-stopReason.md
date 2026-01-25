# realtimekit_stopReason

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `caller` | object | No |  |
| `reason` | enum: API_CALL, INTERNAL_ERROR, ALL_PEERS_LEFT | No | Specifies the reason why the recording stopped. |

## Nested Fields

### `caller`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | No | Name of the user who stopped the recording. |
| `type` | enum: ORGANIZATION, USER | No | The type can be an App or a user. If the type is `user`, then only the `user_Id` and `name` are returned. |
| `user_Id` | string (uuid) | No | The user ID of the person who stopped the recording. |


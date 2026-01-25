# realtimekit_startReason

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `caller` | object | No |  |
| `reason` | enum: API_CALL, RECORD_ON_START | No | Specifies if the recording was started using the "Start a Recording"API or using the parameter RECORD_ON_START in the "Create a meeting" API. 

If the recording is initiated using the "RECORD_ON_START" parameter, the user details will not be populated. |

## Nested Fields

### `caller`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | No | Name of the user who started the recording. |
| `type` | enum: ORGANIZATION, USER | No | The type can be an App or a user. If the type is `user`, then only the `user_Id` and `name` are returned. |
| `user_Id` | string (uuid) | No | The user ID of the person who started the recording. |


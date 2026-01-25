# POST /accounts/{account_id}/realtime/kit/{app_id}/recordings

**Resource:** [Recordings](../resources/Recordings.md)
**Start recording a meeting**
**Operation ID:** `start_recording`

Starts recording a meeting. The meeting can be started by an App admin directly, or a participant with permissions to start a recording, based on the type of authorization used.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | realtimekit_account_identifier | Yes |  |
| `app_id` | path | realtimekit_app_id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |

## Security

- **api_token**

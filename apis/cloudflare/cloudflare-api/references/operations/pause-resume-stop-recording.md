# PUT /accounts/{account_id}/realtime/kit/{app_id}/recordings/{recording_id}

**Resource:** [Recordings](../resources/Recordings.md)
**Pause/Resume/Stop recording**
**Operation ID:** `pause_resume_stop_recording`

Pause/Resume/Stop a given recording ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | realtimekit_account_identifier | Yes |  |
| `app_id` | path | string | Yes | A Cloudflare-generated unique identifier for an item. |
| `recording_id` | path | string | Yes | ID of the recording |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |

## Security

- **api_token**

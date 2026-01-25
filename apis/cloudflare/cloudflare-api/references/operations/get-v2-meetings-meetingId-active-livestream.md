# GET /accounts/{account_id}/realtime/kit/{app_id}/meetings/{meeting_id}/active-livestream

**Resource:** [Live streams](../resources/Live-streams.md)
**Fetch active livestreams for a meeting**
**Operation ID:** `get-v2-meetings-meetingId-active-livestream`

Returns details of all active livestreams for the given meeting ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `meeting_id` | path | string (uuid) | Yes | ID of the meeting |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

## Security

- **api_token**

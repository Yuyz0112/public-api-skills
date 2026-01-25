# POST /accounts/{account_id}/realtime/kit/{app_id}/meetings/{meeting_id}/active-livestream/stop

**Resource:** [Live streams](../resources/Live-streams.md)
**Stop livestreaming a meeting**
**Operation ID:** `stop_livestreaming`

Stops the active livestream of a meeting associated with the given meeting ID. Retreive the meeting ID using the `Create a meeting` API.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `meeting_id` | path | string (uuid) | Yes | ID of the meeting |

## Request Body

**Content Types:** 

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

## Security

- **api_token**

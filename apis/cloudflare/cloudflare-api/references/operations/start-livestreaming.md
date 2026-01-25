# POST /accounts/{account_id}/realtime/kit/{app_id}/meetings/{meeting_id}/livestreams

**Resource:** [Live streams](../resources/Live-streams.md)
**Start livestreaming a meeting**
**Operation ID:** `start-livestreaming`

Starts livestream of a meeting associated with the given meeting ID. Retreive the meeting ID using the `Create a meeting` API.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `meeting_id` | path | string (uuid) | Yes | ID of the meeting |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

## Security

- **api_token**

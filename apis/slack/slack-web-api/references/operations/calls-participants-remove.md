# POST /calls.participants.remove

**Resource:** [calls.participants](../resources/calls-participants.md)
**Operation ID:** `calls_participants_remove`

Registers participants removed from a Call.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | header | string | Yes | Authentication token. Requires scope: `calls:write` |

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: calls:write

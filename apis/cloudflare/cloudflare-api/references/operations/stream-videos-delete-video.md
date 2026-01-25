# DELETE /accounts/{account_id}/stream/{identifier}

**Resource:** [Stream Videos](../resources/Stream-Videos.md)
**Delete video**
**Operation ID:** `stream-videos-delete-video`

Deletes a video and its copies from Cloudflare Stream.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `identifier` | path | stream_identifier | Yes |  |
| `account_id` | path | stream_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete video response. |
| 4XX | Delete video response failure. |

## Security

- **api_email**
- **api_key**
- **api_token**

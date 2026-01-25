# POST /accounts/{account_id}/stream/{identifier}/token

**Resource:** [Stream Videos](../resources/Stream-Videos.md)
**Create signed URL tokens for videos**
**Operation ID:** `stream-videos-create-signed-url-tokens-for-videos`

Creates a signed URL token for a video. If a body is not provided in the request, a token is created with default values.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `identifier` | path | stream_identifier | Yes |  |
| `account_id` | path | stream_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [stream_signed_token_request](../schemas/stream/stream-signed-token-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create signed URL tokens for videos response. |
| 4XX | Create signed URL tokens for videos response failure. |

**Success Response Schema:**

[stream_signed_token_response](../schemas/stream/stream-signed-token-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

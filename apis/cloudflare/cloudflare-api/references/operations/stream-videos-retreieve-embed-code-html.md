# GET /accounts/{account_id}/stream/{identifier}/embed

**Resource:** [Stream Videos](../resources/Stream-Videos.md)
**Retrieve embed Code HTML**
**Operation ID:** `stream-videos-retreieve-embed-code-html`

Fetches an HTML code snippet to embed a video in a web page delivered through Cloudflare. On success, returns an HTML fragment for use on web pages to display a video. On failure, returns a JSON response body.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `identifier` | path | stream_identifier | Yes |  |
| `account_id` | path | stream_account_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Retreieve embed Code HTML response. |
| 4XX | Retreieve embed Code HTML response failure. |

## Security

- **api_email**
- **api_key**
- **api_token**

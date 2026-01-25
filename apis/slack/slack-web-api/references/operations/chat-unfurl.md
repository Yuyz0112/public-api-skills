# POST /chat.unfurl

**Resource:** [chat](../resources/chat.md)
**Operation ID:** `chat_unfurl`

Provide custom unfurl behavior for user-posted URLs

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | header | string | Yes | Authentication token. Requires scope: `links:write` |

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical, minimal success response |
| default | Typical error response |

## Security

- **slackAuth**: links:write

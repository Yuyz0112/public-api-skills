# POST /accounts/{account_id}/ai/tomarkdown

**Resource:** [Workers AI](../resources/Workers-AI.md)
**Convert Files into Markdown**
**Operation ID:** `workers-ai-post-to-markdown`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |

## Request Body

**Content Types:** `application/octet-stream`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Model Schema |
| 400 | Bad Request |

## Security

- **api_token**
- **api_email**
- **api_key**

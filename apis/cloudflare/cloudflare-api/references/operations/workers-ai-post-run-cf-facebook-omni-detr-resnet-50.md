# POST /accounts/{account_id}/ai/run/@cf/facebook/omni-detr-resnet-50

**Resource:** [Workers AI Object Detection](../resources/Workers-AI-Object-Detection.md)
**Execute @cf/facebook/omni-detr-resnet-50 model.**
**Operation ID:** `workers-ai-post-run-cf-facebook-omni-detr-resnet-50`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `queueRequest` | query | string | No |  |
| `tags` | query | string | No |  |

## Request Body

**Content Types:** `application/octet-stream`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Object with user data. |
| 400 | Bad request |

## Security

- **api_token**
- **api_email**
- **api_key**

# POST /accounts/{account_id}/ai/run/@cf/runwayml/stable-diffusion-v1-5-inpainting

**Resource:** [Workers AI Text To Image](../resources/Workers-AI-Text-To-Image.md)
**Execute @cf/runwayml/stable-diffusion-v1-5-inpainting model.**
**Operation ID:** `workers-ai-post-run-cf-runwayml-stable-diffusion-v1-5-inpainting`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `queueRequest` | query | string | No |  |
| `tags` | query | string | No |  |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Object with user data. |
| 400 | Bad request |

## Security

- **api_token**
- **api_email**
- **api_key**

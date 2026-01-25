# GET /accounts/{account_id}/images/v1/{image_id}

**Resource:** [Cloudflare Images](../resources/Cloudflare-Images.md)
**Image details**
**Operation ID:** `cloudflare-images-image-details`

Fetch details for a single image.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `image_id` | path | images_image_identifier | Yes |  |
| `account_id` | path | images_account_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Image details response |
| 4XX | Image details response failure |

**Success Response Schema:**

[images_image_response_single](../schemas/images/images-image-response-single.md)

## Security

- **api_token**
- **api_email**
- **api_key**

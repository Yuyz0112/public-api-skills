# GET /accounts/{account_id}/images/v1/{image_id}/blob

**Resource:** [Cloudflare Images](../resources/Cloudflare-Images.md)
**Base image**
**Operation ID:** `cloudflare-images-base-image`

Fetch base image. For most images this will be the originally uploaded file. For larger images it can be a near-lossless version of the original.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `image_id` | path | images_image_identifier | Yes |  |
| `account_id` | path | images_account_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Base image response. Returns uploaded image data. |
| 4XX | Base image response failure |

## Security

- **api_token**
- **api_email**
- **api_key**

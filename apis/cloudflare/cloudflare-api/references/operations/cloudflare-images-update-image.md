# PATCH /accounts/{account_id}/images/v1/{image_id}

**Resource:** [Cloudflare Images](../resources/Cloudflare-Images.md)
**Update image**
**Operation ID:** `cloudflare-images-update-image`

Update image access control. On access control change, all copies of the image are purged from cache.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `image_id` | path | images_image_identifier | Yes |  |
| `account_id` | path | images_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [images_image_patch_request](../schemas/images/images-image-patch-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update image response |
| 4XX | Update image response failure |

**Success Response Schema:**

[images_image_response_single](../schemas/images/images-image-response-single.md)

## Security

- **api_token**
- **api_email**
- **api_key**

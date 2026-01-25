# DELETE /accounts/{account_id}/images/v1/{image_id}

**Resource:** [Cloudflare Images](../resources/Cloudflare-Images.md)
**Delete image**
**Operation ID:** `cloudflare-images-delete-image`

Delete an image on Cloudflare Images. On success, all copies of the image are deleted and purged from cache.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `image_id` | path | images_image_identifier | Yes |  |
| `account_id` | path | images_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete image response |
| 4XX | Delete image response failure |

**Success Response Schema:**

[images_deleted_response](../schemas/images/images-deleted-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**

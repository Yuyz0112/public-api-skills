# DELETE /accounts/{account_id}/images/v1/variants/{variant_id}

**Resource:** [Cloudflare Images Variants](../resources/Cloudflare-Images-Variants.md)
**Delete a variant**
**Operation ID:** `cloudflare-images-variants-delete-a-variant`

Deleting a variant purges the cache for all images associated with the variant.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `variant_id` | path | images_image_variant_identifier | Yes |  |
| `account_id` | path | images_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete a variant response |
| 4XX | Delete a variant response failure |

**Success Response Schema:**

[images_deleted_response](../schemas/images/images-deleted-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**

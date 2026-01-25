# PATCH /accounts/{account_id}/images/v1/variants/{variant_id}

**Resource:** [Cloudflare Images Variants](../resources/Cloudflare-Images-Variants.md)
**Update a variant**
**Operation ID:** `cloudflare-images-variants-update-a-variant`

Updating a variant purges the cache for all images associated with the variant.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `variant_id` | path | images_image_variant_identifier | Yes |  |
| `account_id` | path | images_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [images_image_variant_patch_request](../schemas/images/images-image-variant-patch-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update a variant response |
| 4XX | Update a variant response failure |

**Success Response Schema:**

[images_image_variant_simple_response](../schemas/images/images-image-variant-simple-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**

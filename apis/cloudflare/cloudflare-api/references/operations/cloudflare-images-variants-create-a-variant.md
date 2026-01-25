# POST /accounts/{account_id}/images/v1/variants

**Resource:** [Cloudflare Images Variants](../resources/Cloudflare-Images-Variants.md)
**Create a variant**
**Operation ID:** `cloudflare-images-variants-create-a-variant`

Specify variants that allow you to resize images for different use cases.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | images_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [images_image_variant_definition](../schemas/images/images-image-variant-definition.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create a variant response |
| 4XX | Create a variant response failure |

**Success Response Schema:**

[images_image_variant_simple_response](../schemas/images/images-image-variant-simple-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**

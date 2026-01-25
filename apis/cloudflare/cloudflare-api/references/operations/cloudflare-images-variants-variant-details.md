# GET /accounts/{account_id}/images/v1/variants/{variant_id}

**Resource:** [Cloudflare Images Variants](../resources/Cloudflare-Images-Variants.md)
**Variant details**
**Operation ID:** `cloudflare-images-variants-variant-details`

Fetch details for a single variant.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `variant_id` | path | images_image_variant_identifier | Yes |  |
| `account_id` | path | images_account_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Variant details response |
| 4XX | Variant details response failure |

**Success Response Schema:**

[images_image_variant_simple_response](../schemas/images/images-image-variant-simple-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**

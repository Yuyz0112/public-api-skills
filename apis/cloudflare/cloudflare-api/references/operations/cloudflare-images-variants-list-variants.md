# GET /accounts/{account_id}/images/v1/variants

**Resource:** [Cloudflare Images Variants](../resources/Cloudflare-Images-Variants.md)
**List variants**
**Operation ID:** `cloudflare-images-variants-list-variants`

Lists existing variants.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | images_account_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List variants response |
| 4XX | List variants response failure |

**Success Response Schema:**

[images_image_variant_list_response](../schemas/images/images-image-variant-list-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**

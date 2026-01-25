# GET /accounts/{account_id}/images/v1/keys

**Resource:** [Cloudflare Images Keys](../resources/Cloudflare-Images-Keys.md)
**List Signing Keys**
**Operation ID:** `cloudflare-images-keys-list-signing-keys`

Lists your signing keys. These can be found on your Cloudflare Images dashboard.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | images_account_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Signing Keys response |
| 4XX | List Signing Keys response failure |

**Success Response Schema:**

[images_image_key_response_collection](../schemas/images/images-image-key-response-collection.md)

## Security

- **api_token**
- **api_email**
- **api_key**

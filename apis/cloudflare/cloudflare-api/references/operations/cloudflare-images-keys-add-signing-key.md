# PUT /accounts/{account_id}/images/v1/keys/{signing_key_name}

**Resource:** [Cloudflare Images Keys](../resources/Cloudflare-Images-Keys.md)
**Create a new Signing Key**
**Operation ID:** `cloudflare-images-keys-add-signing-key`

Create a new signing key with specified name. Returns all keys available.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `signing_key_name` | path | images_signing_key_identifier | Yes |  |
| `account_id` | path | images_account_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Add Signing Key response |
| 4XX | Add Signing Key response failure |

**Success Response Schema:**

[images_image_key_response_collection](../schemas/images/images-image-key-response-collection.md)

## Security

- **api_token**
- **api_email**
- **api_key**

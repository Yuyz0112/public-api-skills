# DELETE /accounts/{account_id}/images/v1/keys/{signing_key_name}

**Resource:** [Cloudflare Images Keys](../resources/Cloudflare-Images-Keys.md)
**Delete Signing Key**
**Operation ID:** `cloudflare-images-keys-delete-signing-key`

Delete signing key with specified name. Returns all keys available.
When last key is removed, a new default signing key will be generated.


## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `signing_key_name` | path | images_signing_key_identifier | Yes |  |
| `account_id` | path | images_account_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete Signing Key response |
| 4XX | Delete Signing Key response failure |

**Success Response Schema:**

[images_image_key_response_collection](../schemas/images/images-image-key-response-collection.md)

## Security

- **api_token**
- **api_email**
- **api_key**

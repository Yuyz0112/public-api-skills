# POST /accounts/{account_id}/access/keys/rotate

**Resource:** [Access key configuration](../resources/Access-key-configuration.md)
**Rotate Access keys**
**Operation ID:** `access-key-configuration-rotate-access-keys`

Perfoms a key rotation for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | access_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Rotate Access keys response |
| 4XX | Rotate Access keys response failure |

**Success Response Schema:**

[access_keys_components-schemas-single_response](../schemas/access/access-keys-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

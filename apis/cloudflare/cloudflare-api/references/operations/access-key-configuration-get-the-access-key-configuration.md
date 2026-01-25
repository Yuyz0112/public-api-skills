# GET /accounts/{account_id}/access/keys

**Resource:** [Access key configuration](../resources/Access-key-configuration.md)
**Get the Access key configuration**
**Operation ID:** `access-key-configuration-get-the-access-key-configuration`

Gets the Access key rotation settings for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | access_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get the Access key configuration response |
| 4XX | Get the Access key configuration response failure |

**Success Response Schema:**

[access_keys_components-schemas-single_response](../schemas/access/access-keys-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

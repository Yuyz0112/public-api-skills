# PUT /accounts/{account_id}/access/keys

**Resource:** [Access key configuration](../resources/Access-key-configuration.md)
**Update the Access key configuration**
**Operation ID:** `access-key-configuration-update-the-access-key-configuration`

Updates the Access key rotation settings for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | access_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update the Access key configuration response |
| 4XX | Update the Access key configuration response failure |

**Success Response Schema:**

[access_keys_components-schemas-single_response](../schemas/access/access-keys-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

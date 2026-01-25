# GET /accounts/{account_id}/access/organizations

**Resource:** [Zero Trust organization](../resources/Zero-Trust-organization.md)
**Get your Zero Trust organization**
**Operation ID:** `zero-trust-organization-get-your-zero-trust-organization`

Returns the configuration for your Zero Trust organization.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | access_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get your Zero Trust organization response |
| 4XX | Get your Zero Trust organization response failure |

**Success Response Schema:**

[access_single_response](../schemas/access/access-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

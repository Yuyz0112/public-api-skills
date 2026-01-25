# PUT /accounts/{account_id}/access/organizations

**Resource:** [Zero Trust organization](../resources/Zero-Trust-organization.md)
**Update your Zero Trust organization**
**Operation ID:** `zero-trust-organization-update-your-zero-trust-organization`

Updates the configuration for your Zero Trust organization.

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
| 200 | Update your Zero Trust organization response |
| 4XX | Update your Zero Trust organization response failure |

**Success Response Schema:**

[access_single_response](../schemas/access/access-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

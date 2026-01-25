# POST /accounts/{account_id}/access/organizations

**Resource:** [Zero Trust organization](../resources/Zero-Trust-organization.md)
**Create your Zero Trust organization**
**Operation ID:** `zero-trust-organization-create-your-zero-trust-organization`

Sets up a Zero Trust organization for your account.

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
| 201 | Create your Zero Trust organization response |
| 4XX | Create your Zero Trust organization response failure |

**Success Response Schema:**

[access_single_response](../schemas/access/access-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

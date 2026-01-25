# POST /accounts/{account_id}/access/organizations/revoke_user

**Resource:** [Zero Trust organization](../resources/Zero-Trust-organization.md)
**Revoke all Access tokens for a user**
**Operation ID:** `zero-trust-organization-revoke-all-access-tokens-for-a-user`

Revokes a user's access across all applications.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | access_identifier | Yes |  |
| `devices` | query | boolean | No | When set to `true`, all devices associated with the user will be revoked. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Revoke all Access tokens for a user response |
| 4xx | Revoke all Access tokens for a user response failure |

**Success Response Schema:**

[access_empty_response](../schemas/access/access-empty-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

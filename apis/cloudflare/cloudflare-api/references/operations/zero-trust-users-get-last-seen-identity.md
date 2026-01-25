# GET /accounts/{account_id}/access/users/{user_id}/last_seen_identity

**Resource:** [Zero Trust users](../resources/Zero-Trust-users.md)
**Get last seen identity**
**Operation ID:** `zero-trust-users-get-last-seen-identity`

Get last seen identity for a single user.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `user_id` | path | access_uuid | Yes |  |
| `account_id` | path | access_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get active session response |
| 4XX | Get active session response failure |

**Success Response Schema:**

[access_last_seen_identity_response](../schemas/access/access-last-seen-identity-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

# GET /accounts/{account_id}/access/users/{user_id}/active_sessions/{nonce}

**Resource:** [Zero Trust users](../resources/Zero-Trust-users.md)
**Get single active session**
**Operation ID:** `zero-trust-users-get-active-session`

Get an active session for a single user.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `user_id` | path | access_uuid | Yes |  |
| `account_id` | path | access_identifier | Yes |  |
| `nonce` | path | access_nonce | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get active session response |
| 4XX | Get active session response failure |

**Success Response Schema:**

[access_active_session_response](../schemas/access/access-active-session-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

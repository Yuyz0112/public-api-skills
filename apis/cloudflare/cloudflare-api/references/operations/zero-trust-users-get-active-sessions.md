# GET /accounts/{account_id}/access/users/{user_id}/active_sessions

**Resource:** [Zero Trust users](../resources/Zero-Trust-users.md)
**Get active sessions**
**Operation ID:** `zero-trust-users-get-active-sessions`

Get active sessions for a single user.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `user_id` | path | access_uuid | Yes |  |
| `account_id` | path | access_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get active sessions response |
| 4XX | Get active sessions response failure |

**Success Response Schema:**

[access_active_sessions_response](../schemas/access/access-active-sessions-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

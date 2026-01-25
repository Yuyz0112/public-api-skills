# GET /accounts/{account_id}/access/users/{user_id}/failed_logins

**Resource:** [Zero Trust users](../resources/Zero-Trust-users.md)
**Get failed logins**
**Operation ID:** `zero-trust-users-get-failed-logins`

Get all failed login attempts for a single user.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `user_id` | path | access_uuid | Yes |  |
| `account_id` | path | access_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get failed logins response |
| 4XX | Get failed logins response failure |

**Success Response Schema:**

[access_failed_login_response](../schemas/access/access-failed-login-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

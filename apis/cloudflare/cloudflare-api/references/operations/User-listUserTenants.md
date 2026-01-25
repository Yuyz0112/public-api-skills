# GET /users/tenants

**Resource:** [User](../resources/User.md)
**List user tenants**
**Operation ID:** `User_listUserTenants`

Retrieves list of tenants the authenticated user / method has access to.

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| 4XX | An unexpected error response. |

## Security

- **api_email**
- **api_key**

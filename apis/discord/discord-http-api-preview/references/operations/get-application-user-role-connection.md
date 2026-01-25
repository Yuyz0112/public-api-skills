# GET /users/@me/applications/{application_id}/role-connection

**Resource:** [users](../resources/users.md)
**Operation ID:** `get_application_user_role_connection`

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for get_application_user_role_connection |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[ApplicationUserRoleConnectionResponse](../schemas/Application/ApplicationUserRoleConnectionResponse.md)

## Security

- **OAuth2**: role_connections.write

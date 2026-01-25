# PUT /users/@me/applications/{application_id}/role-connection

**Resource:** [users](../resources/users.md)
**Operation ID:** `update_application_user_role_connection`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [UpdateApplicationUserRoleConnectionRequest](../schemas/Update/UpdateApplicationUserRoleConnectionRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for update_application_user_role_connection |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[ApplicationUserRoleConnectionResponse](../schemas/Application/ApplicationUserRoleConnectionResponse.md)

## Security

- **OAuth2**: role_connections.write

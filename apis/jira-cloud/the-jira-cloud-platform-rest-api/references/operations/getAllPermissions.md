# GET /rest/api/3/permissions

**Resource:** [Permissions](../resources/Permissions.md)
**Get all permissions**
**Operation ID:** `getAllPermissions`

Returns all permissions, including:

 *  global permissions.
 *  project permissions.
 *  global permissions added by plugins.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** None.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |

**Success Response Schema:**

[Permissions](../schemas/Permissions/Permissions.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

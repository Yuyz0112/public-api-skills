# GET /rest/api/3/applicationrole/{key}

**Resource:** [Application roles](../resources/Application-roles.md)
**Get application role**
**Operation ID:** `getApplicationRole`

Returns an application role.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `key` | path | string | Yes | The key of the application role. Use the [Get all application roles](#api-rest-api-3-applicationrole-get) operation to get the key for each application role. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user is not an administrator. |
| 404 | Returned if the role is not found. |

**Success Response Schema:**

[ApplicationRole](../schemas/Application/ApplicationRole.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

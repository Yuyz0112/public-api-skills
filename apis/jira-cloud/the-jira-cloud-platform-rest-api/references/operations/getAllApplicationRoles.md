# GET /rest/api/3/applicationrole

**Resource:** [Application roles](../resources/Application-roles.md)
**Get all application roles**
**Operation ID:** `getAllApplicationRoles`

Returns all application roles. In Jira, application roles are managed using the [Application access configuration](https://confluence.atlassian.com/x/3YxjL) page.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user is not an administrator. |

**Success Response Schema:**

Array of [ApplicationRole](../schemas/Application/ApplicationRole.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

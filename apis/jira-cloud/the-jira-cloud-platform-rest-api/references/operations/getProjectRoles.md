# GET /rest/api/3/project/{projectIdOrKey}/role

**Resource:** [Project roles](../resources/Project-roles.md)
**Get project roles for project**
**Operation ID:** `getProjectRoles`

Returns a list of [project roles](https://support.atlassian.com/jira-cloud-administration/docs/manage-project-roles/) for the project returning the name and self URL for each role.

Note that all project roles are shared with all projects in Jira Cloud. See [Get all project roles](#api-rest-api-3-role-get) for more information.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** *Administer Projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for any project on the site or *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `projectIdOrKey` | path | string | Yes | The project ID or project key (case sensitive). |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing or if the user lacks administrative permissions for the project. |
| 404 | Returned if the project is not found or or if the user does not have administrative permissions for the project. |

## Security

- **basicAuth**
- **OAuth2**: read:jira-work

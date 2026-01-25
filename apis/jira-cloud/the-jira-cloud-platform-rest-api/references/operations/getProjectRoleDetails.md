# GET /rest/api/3/project/{projectIdOrKey}/roledetails

**Resource:** [Project roles](../resources/Project-roles.md)
**Get project role details**
**Operation ID:** `getProjectRoleDetails`

Returns all [project roles](https://support.atlassian.com/jira-cloud-administration/docs/manage-project-roles/) and the details for each role. Note that the list of project roles is common to all projects.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg) or *Administer projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `projectIdOrKey` | path | string | Yes | The project ID or project key (case sensitive). |
| `currentMember` | query | boolean | No | Whether the roles should be filtered to include only those the user is assigned to. |
| `excludeConnectAddons` | query | boolean | No |  |
| `excludeOtherServiceRoles` | query | boolean | No | Do not return the default JSM company-managed space from CSM spaces, or the default CSM roles from JSM spaces. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if the project is not found or if the user does not have the necessary permissions for the project. |

**Success Response Schema:**

Array of [ProjectRoleDetails](../schemas/Project/ProjectRoleDetails.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work

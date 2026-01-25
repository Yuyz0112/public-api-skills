# DELETE /rest/api/3/project/{projectIdOrKey}

**Resource:** [Projects](../resources/Projects.md)
**Delete project**
**Operation ID:** `deleteProject`

Deletes a project.

You can't delete a project if it's archived. To delete an archived project, restore the project and then delete it. To restore a project, use the Jira UI.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `projectIdOrKey` | path | string | Yes | The project ID or project key (case sensitive). |
| `enableUndo` | query | boolean | No | Whether this project is placed in the Jira recycle bin where it will be available for restoration. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the project is deleted. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if the project is not found or the user does not have permission to delete it. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

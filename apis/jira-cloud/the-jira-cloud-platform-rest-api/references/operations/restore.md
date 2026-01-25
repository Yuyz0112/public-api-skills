# POST /rest/api/3/project/{projectIdOrKey}/restore

**Resource:** [Projects](../resources/Projects.md)
**Restore deleted or archived project**
**Operation ID:** `restore`

Restores a project that has been archived or placed in the Jira recycle bin.

**[Permissions](#permissions) required:**

 *  *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg)for Company managed projects.
 *  *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg) or *Administer projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project for Team managed projects.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `projectIdOrKey` | path | string | Yes | The project ID or project key (case sensitive). |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if the project is not found or the user does not have the necessary permission. |

**Success Response Schema:**

[Project](../schemas/Project/Project.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

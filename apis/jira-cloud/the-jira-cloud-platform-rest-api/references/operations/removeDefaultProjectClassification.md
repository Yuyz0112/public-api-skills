# DELETE /rest/api/3/project/{projectIdOrKey}/classification-level/default

**Resource:** [Project classification levels](../resources/Project-classification-levels.md)
**Remove the default data classification level from a project**
**Operation ID:** `removeDefaultProjectClassification`

Remove the default data classification level for a project.

**[Permissions](#permissions) required:**

 *  *Administer projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project.
 *  *Administer jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `projectIdOrKey` | path | string | Yes | The project ID or project key (case-sensitive). |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the user does not have the necessary permission. |
| 404 | Returned if the project is not found. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-project

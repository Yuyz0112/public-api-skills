# GET /rest/api/3/project/{projectIdOrKey}/classification-level/default

**Resource:** [Project classification levels](../resources/Project-classification-levels.md)
**Get the default data classification level of a project**
**Operation ID:** `getDefaultProjectClassification`

Returns the default data classification for a project.

**[Permissions](#permissions) required:**

 *  *Browse Projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project.
 *  *Administer projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project.
 *  *Administer jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `projectIdOrKey` | path | string | Yes | The project ID or project key (case-sensitive). |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the user does not have the necessary permission. |
| 404 | Returned if the project is not found. |

## Security

- **basicAuth**
- **OAuth2**: read:jira-work

# PUT /rest/api/3/project/{projectIdOrKey}/classification-level/default

**Resource:** [Project classification levels](../resources/Project-classification-levels.md)
**Update the default data classification level of a project**
**Operation ID:** `updateDefaultProjectClassification`

Updates the default data classification level for a project.

**[Permissions](#permissions) required:**

 *  *Administer projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project.
 *  *Administer jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `projectIdOrKey` | path | string | Yes | The project ID or project key (case-sensitive). |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [UpdateDefaultProjectClassificationBean](../schemas/Update/UpdateDefaultProjectClassificationBean.md)

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

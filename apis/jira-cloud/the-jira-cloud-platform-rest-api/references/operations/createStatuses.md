# POST /rest/api/3/statuses

**Resource:** [Status](../resources/Status.md)
**Bulk create statuses**
**Operation ID:** `createStatuses`

Creates statuses for a global or project scope.

**[Permissions](#permissions) required:**

 *  *Administer projects* [project permission.](https://confluence.atlassian.com/x/yodKLg)
 *  *Administer Jira* [project permission.](https://confluence.atlassian.com/x/yodKLg)

## Request Body

Details of the statuses being created and their scope.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [StatusCreateRequest](../schemas/Status/StatusCreateRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing, or the caller doesn't have permissions to perform the operation. |
| 409 | Returned if another workflow configuration update task is ongoing. |

**Success Response Schema:**

Array of [JiraStatus](../schemas/Jira/JiraStatus.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

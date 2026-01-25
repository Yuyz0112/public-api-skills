# PUT /rest/api/3/statuses

**Resource:** [Status](../resources/Status.md)
**Bulk update statuses**
**Operation ID:** `updateStatuses`

Updates statuses by ID.

**[Permissions](#permissions) required:**

 *  *Administer projects* [project permission.](https://confluence.atlassian.com/x/yodKLg)
 *  *Administer Jira* [project permission.](https://confluence.atlassian.com/x/yodKLg)

## Request Body

The list of statuses that will be updated.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [StatusUpdateRequest](../schemas/Status/StatusUpdateRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing, or the caller doesn't have permissions to perform the operation. |
| 409 | Returned if another workflow configuration update task is ongoing. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

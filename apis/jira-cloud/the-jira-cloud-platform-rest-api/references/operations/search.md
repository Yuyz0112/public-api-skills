# GET /rest/api/3/statuses/search

**Resource:** [Status](../resources/Status.md)
**Search statuses paginated**
**Operation ID:** `search`

Returns a [paginated](https://developer.atlassian.com/cloud/jira/platform/rest/v3/intro/#pagination) list of statuses that match a search on name or project.

**[Permissions](#permissions) required:**

 *  *Administer projects* [project permission.](https://confluence.atlassian.com/x/yodKLg)
 *  *Administer Jira* [project permission.](https://confluence.atlassian.com/x/yodKLg)

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `projectId` | query | string | No | The project the status is part of or null for global statuses. |
| `startAt` | query | integer (int64) | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return per page. |
| `searchString` | query | string | No | Term to match status names against or null to search for all statuses in the search scope. |
| `statusCategory` | query | string | No | Category of the status to filter by. The supported values are: `TODO`, `IN_PROGRESS`, and `DONE`. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing, or the caller doesn't have permissions to perform the operation. |

**Success Response Schema:**

[PageOfStatuses](../schemas/Page/PageOfStatuses.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

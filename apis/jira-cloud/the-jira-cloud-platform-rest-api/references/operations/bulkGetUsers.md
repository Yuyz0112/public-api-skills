# GET /rest/api/3/user/bulk

**Resource:** [Users](../resources/Users.md)
**Bulk get users**
**Operation ID:** `bulkGetUsers`

Returns a [paginated](#pagination) list of the users specified by one or more account IDs.

**[Permissions](#permissions) required:** Permission to access Jira.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `startAt` | query | integer (int64) | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return per page. |
| `username` | query | string[] | No | This parameter is no longer available and will be removed from the documentation soon. See the [deprecation notice](https://developer.atlassian.com/cloud/jira/platform/deprecation-notice-user-privacy-api-migration-guide/) for details. |
| `key` | query | string[] | No | This parameter is no longer available and will be removed from the documentation soon. See the [deprecation notice](https://developer.atlassian.com/cloud/jira/platform/deprecation-notice-user-privacy-api-migration-guide/) for details. |
| `accountId` | query | string[] | Yes | The account ID of a user. To specify multiple users, pass multiple `accountId` parameters. For example, `accountId=5b10a2844c20165700ede21g&accountId=5b10ac8d82e05b22cc7d4ef5`. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if `accountID` is missing. |
| 401 | Returned if the authentication credentials are incorrect or missing. |

**Success Response Schema:**

[PageBeanUser](../schemas/Page/PageBeanUser.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-user

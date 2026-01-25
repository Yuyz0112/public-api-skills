# GET /rest/api/3/group/bulk

**Resource:** [Groups](../resources/Groups.md)
**Bulk get groups**
**Operation ID:** `bulkGetGroups`

Returns a [paginated](#pagination) list of groups.

**[Permissions](#permissions) required:** *Browse users and groups* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `startAt` | query | integer (int64) | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return per page. |
| `groupId` | query | string[] | No | The ID of a group. To specify multiple IDs, pass multiple `groupId` parameters. For example, `groupId=5b10a2844c20165700ede21g&groupId=5b10ac8d82e05b22cc7d4ef5`. |
| `groupName` | query | string[] | No | The name of a group. To specify multiple names, pass multiple `groupName` parameters. For example, `groupName=administrators&groupName=jira-software-users`. |
| `accessType` | query | string | No | The access level of a group. Valid values: 'site-admin', 'admin', 'user'. |
| `applicationKey` | query | string | No | The application key of the product user groups to search for. Valid values: 'jira-servicedesk', 'jira-software', 'jira-product-discovery', 'jira-core'. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 500 | Returned if the group with the given access level can't be retrieved. |

**Success Response Schema:**

[PageBeanGroupDetails](../schemas/Page/PageBeanGroupDetails.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-user

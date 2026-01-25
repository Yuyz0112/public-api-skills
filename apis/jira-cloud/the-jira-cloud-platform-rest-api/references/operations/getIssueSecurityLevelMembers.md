# GET /rest/api/3/issuesecurityschemes/{issueSecuritySchemeId}/members

**Resource:** [Issue security level](../resources/Issue-security-level.md)
**Get issue security level members by issue security scheme**
**Operation ID:** `getIssueSecurityLevelMembers`

Returns issue security level members.

Only issue security level members in context of classic projects are returned.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `issueSecuritySchemeId` | path | integer (int64) | Yes | The ID of the issue security scheme. Use the [Get issue security schemes](#api-rest-api-3-issuesecurityschemes-get) operation to get a list of issue security scheme IDs. |
| `startAt` | query | integer (int64) | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return per page. |
| `issueSecurityLevelId` | query | string[] | No | The list of issue security level IDs. To include multiple issue security levels separate IDs with ampersand: `issueSecurityLevelId=10000&issueSecurityLevelId=10001`. |
| `expand` | query | string | No | Use expand to include additional information in the response. This parameter accepts a comma-separated list. Expand options include:

 *  `all` Returns all expandable information.
 *  `field` Returns information about the custom field granted the permission.
 *  `group` Returns information about the group that is granted the permission.
 *  `projectRole` Returns information about the project role granted the permission.
 *  `user` Returns information about the user who is granted the permission. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if no issue security level members are found. |

**Success Response Schema:**

[PageBeanIssueSecurityLevelMember](../schemas/Page/PageBeanIssueSecurityLevelMember.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

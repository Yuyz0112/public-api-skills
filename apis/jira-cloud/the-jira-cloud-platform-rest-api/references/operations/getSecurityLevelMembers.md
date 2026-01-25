# GET /rest/api/3/issuesecurityschemes/level/member

**Resource:** [Issue security schemes](../resources/Issue-security-schemes.md)
**Get issue security level members**
**Operation ID:** `getSecurityLevelMembers`

Returns a [paginated](#pagination) list of issue security level members.

Only issue security level members in the context of classic projects are returned.

Filtering using parameters is inclusive: if you specify both security scheme IDs and level IDs, the result will include all issue security level members from the specified schemes and levels.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `startAt` | query | string | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | string | No | The maximum number of items to return per page. |
| `id` | query | string[] | No | The list of issue security level member IDs. To include multiple issue security level members separate IDs with an ampersand: `id=10000&id=10001`. |
| `schemeId` | query | string[] | No | The list of issue security scheme IDs. To include multiple issue security schemes separate IDs with an ampersand: `schemeId=10000&schemeId=10001`. |
| `levelId` | query | string[] | No | The list of issue security level IDs. To include multiple issue security levels separate IDs with an ampersand: `levelId=10000&levelId=10001`. |
| `expand` | query | string | No | Use expand to include additional information in the response. This parameter accepts a comma-separated list. Expand options include:

 *  `all` Returns all expandable information
 *  `field` Returns information about the custom field granted the permission
 *  `group` Returns information about the group that is granted the permission
 *  `projectRole` Returns information about the project role granted the permission
 *  `user` Returns information about the user who is granted the permission |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user doesn't have the necessary permission. |

**Success Response Schema:**

[PageBeanSecurityLevelMember](../schemas/Page/PageBeanSecurityLevelMember.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

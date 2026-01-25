# GET /rest/api/3/issuetypescreenscheme/mapping

**Resource:** [Issue type screen schemes](../resources/Issue-type-screen-schemes.md)
**Get issue type screen scheme items**
**Operation ID:** `getIssueTypeScreenSchemeMappings`

Returns a [paginated](#pagination) list of issue type screen scheme items.

Only issue type screen schemes used in classic projects are returned.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `startAt` | query | integer (int64) | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return per page. |
| `issueTypeScreenSchemeId` | query | integer[] | No | The list of issue type screen scheme IDs. To include multiple issue type screen schemes, separate IDs with ampersand: `issueTypeScreenSchemeId=10000&issueTypeScreenSchemeId=10001`. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the required permissions. |

**Success Response Schema:**

[PageBeanIssueTypeScreenSchemeItem](../schemas/Page/PageBeanIssueTypeScreenSchemeItem.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

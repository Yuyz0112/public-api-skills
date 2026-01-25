# GET /rest/api/3/issuetypescreenscheme/{issueTypeScreenSchemeId}/project

**Resource:** [Issue type screen schemes](../resources/Issue-type-screen-schemes.md)
**Get issue type screen scheme projects**
**Operation ID:** `getProjectsForIssueTypeScreenScheme`

Returns a [paginated](#pagination) list of projects associated with an issue type screen scheme.

Only company-managed projects associated with an issue type screen scheme are returned.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `issueTypeScreenSchemeId` | path | integer (int64) | Yes | The ID of the issue type screen scheme. |
| `startAt` | query | integer (int64) | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return per page. |
| `query` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the required permissions. |

**Success Response Schema:**

[PageBeanProjectDetails](../schemas/Page/PageBeanProjectDetails.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

# GET /rest/api/3/issuetypescheme/mapping

**Resource:** [Issue type schemes](../resources/Issue-type-schemes.md)
**Get issue type scheme items**
**Operation ID:** `getIssueTypeSchemesMapping`

Returns a [paginated](#pagination) list of issue type scheme items.

Only issue type scheme items used in classic projects are returned.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `startAt` | query | integer (int64) | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return per page. |
| `issueTypeSchemeId` | query | integer[] | No | The list of issue type scheme IDs. To include multiple IDs, provide an ampersand-separated list. For example, `issueTypeSchemeId=10000&issueTypeSchemeId=10001`. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the required permissions. |

**Success Response Schema:**

[PageBeanIssueTypeSchemeMapping](../schemas/Page/PageBeanIssueTypeSchemeMapping.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

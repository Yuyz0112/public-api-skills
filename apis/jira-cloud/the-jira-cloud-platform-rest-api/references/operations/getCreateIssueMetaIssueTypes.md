# GET /rest/api/3/issue/createmeta/{projectIdOrKey}/issuetypes

**Resource:** [Issues](../resources/Issues.md)
**Get create metadata issue types for a project**
**Operation ID:** `getCreateIssueMetaIssueTypes`

Returns a page of issue type metadata for a specified project. Use the information to populate the requests in [ Create issue](#api-rest-api-3-issue-post) and [Create issues](#api-rest-api-3-issue-bulk-post).

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** *Create issues* [project permission](https://confluence.atlassian.com/x/yodKLg) in the requested projects.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `projectIdOrKey` | path | string | Yes | The ID or key of the project. |
| `startAt` | query | integer (int32) | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return per page. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |

**Success Response Schema:**

[PageOfCreateMetaIssueTypes](../schemas/Page/PageOfCreateMetaIssueTypes.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work

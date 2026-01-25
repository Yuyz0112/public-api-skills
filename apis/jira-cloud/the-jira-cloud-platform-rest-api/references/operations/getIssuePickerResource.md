# GET /rest/api/3/issue/picker

**Resource:** [Issue search](../resources/Issue-search.md)
**Get issue picker suggestions**
**Operation ID:** `getIssuePickerResource`

Returns lists of issues matching a query string. Use this resource to provide auto-completion suggestions when the user is looking for an issue using a word or string.

This operation returns two lists:

 *  `History Search` which includes issues from the user's history of created, edited, or viewed issues that contain the string in the `query` parameter.
 *  `Current Search` which includes issues that match the JQL expression in `currentJQL` and contain the string in the `query` parameter.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** None.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `query` | query | string | No | A string to match against text fields in the issue such as title, description, or comments. |
| `currentJQL` | query | string | No | A JQL query defining a list of issues to search for the query term. Note that `username` and `userkey` cannot be used as search terms for this parameter, due to privacy reasons. Use `accountId` instead. |
| `currentIssueKey` | query | string | No | The key of an issue to exclude from search results. For example, the issue the user is viewing when they perform this query. |
| `currentProjectId` | query | string | No | The ID of a project that suggested issues must belong to. |
| `showSubTasks` | query | boolean | No | Indicate whether to include subtasks in the suggestions list. |
| `showSubTaskParent` | query | boolean | No | When `currentIssueKey` is a subtask, whether to include the parent issue in the suggestions if it matches the query. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |

**Success Response Schema:**

[IssuePickerSuggestions](../schemas/Issue/IssuePickerSuggestions.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work

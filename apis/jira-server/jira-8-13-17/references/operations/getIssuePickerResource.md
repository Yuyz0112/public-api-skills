# GET /issue/picker

**Resource:** [issue](../resources/issue.md)
**Operation ID:** `getIssuePickerResource`

Returns suggested issues which match the auto-completion query for the user which executes this request. This REST
 method will check the user's history and the user's browsing context and select this issues, which match the query.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `query` | query | string | No | the query. |
| `currentJQL` | query | string | No | the JQL in context of which the request is executed. Only issues which match this JQL query will be included in results. |
| `currentIssueKey` | query | string | No | the key of the issue in context of which the request is executed. The issue which is in context will not be included in the auto-completion result, even if it matches the query. |
| `currentProjectId` | query | string | No | the id of the project in context of which the request is executed. Suggested issues will be only from this project. |
| `showSubTasks` | query | boolean | No | if set to false, subtasks will not be included in the list. |
| `showSubTaskParent` | query | boolean | No | if set to false and request is executed in context of a subtask, the parent issue will not be included in the auto-completion result, even if it matches the query. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |


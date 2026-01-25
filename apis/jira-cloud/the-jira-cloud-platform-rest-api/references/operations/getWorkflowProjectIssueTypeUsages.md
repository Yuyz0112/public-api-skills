# GET /rest/api/3/workflow/{workflowId}/project/{projectId}/issueTypeUsages

**Resource:** [Workflows](../resources/Workflows.md)
**Get issue types in a project that are using a given workflow**
**Operation ID:** `getWorkflowProjectIssueTypeUsages`

Returns a page of issue types using a given workflow within a project.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `workflowId` | path | string | Yes | The workflow ID |
| `projectId` | path | integer (int64) | Yes | The project ID |
| `nextPageToken` | query | string | No | The cursor for pagination |
| `maxResults` | query | integer (int32) | No | The maximum number of results to return. Must be an integer between 1 and 200. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing, or the caller doesn't have permissions to perform the operation. |
| 404 | Returned if the workflow with the given ID does not exist. |

**Success Response Schema:**

[WorkflowProjectIssueTypeUsageDTO](../schemas/Workflow/WorkflowProjectIssueTypeUsageDTO.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

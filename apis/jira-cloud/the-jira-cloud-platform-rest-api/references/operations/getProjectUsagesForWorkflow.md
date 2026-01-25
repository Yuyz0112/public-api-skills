# GET /rest/api/3/workflow/{workflowId}/projectUsages

**Resource:** [Workflows](../resources/Workflows.md)
**Get projects using a given workflow**
**Operation ID:** `getProjectUsagesForWorkflow`

Returns a page of projects using a given workflow.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `workflowId` | path | string | Yes | The workflow ID |
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

[WorkflowProjectUsageDTO](../schemas/Workflow/WorkflowProjectUsageDTO.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

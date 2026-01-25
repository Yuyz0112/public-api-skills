# GET /rest/api/3/workflowscheme/{workflowSchemeId}/projectUsages

**Resource:** [Workflow schemes](../resources/Workflow-schemes.md)
**Get projects which are using a given workflow scheme**
**Operation ID:** `getProjectUsagesForWorkflowScheme`

Returns a page of projects using a given workflow scheme.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `workflowSchemeId` | path | string | Yes | The workflow scheme ID |
| `nextPageToken` | query | string | No | The cursor for pagination |
| `maxResults` | query | integer (int32) | No | The maximum number of results to return. Must be an integer between 1 and 200. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing, or the caller doesn't have permissions to perform the operation. |
| 404 | Returned if the workflow scheme with the given ID does not exist. |

**Success Response Schema:**

[WorkflowSchemeProjectUsageDTO](../schemas/Workflow/WorkflowSchemeProjectUsageDTO.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

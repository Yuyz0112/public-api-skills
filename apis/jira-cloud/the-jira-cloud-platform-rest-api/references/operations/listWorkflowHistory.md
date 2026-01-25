# POST /rest/api/3/workflow/history/list

**Resource:** [Workflows](../resources/Workflows.md)
**List workflow history entries**
**Operation ID:** `listWorkflowHistory`

Returns a list of workflow history entries for a specified workflow id.

**Note:** Stored workflow data expires after 28 days. Additionally, no data from before the 30th of October 2025 is available.

**[Permissions](#permissions) required:**

 *  *Administer Jira* global permission to access all, including project-scoped, workflows
 *  At least one of the *Administer projects* and *View (read-only) workflow* project permissions to access project-scoped workflows

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string | No | Use [expand](#expansion) to include additional information in the response. This parameter accepts a comma-separated list. Expand options include:

 *  `includeIntermediateWorkflows` Includes intermediate workflow versions that are sometimes created during workflow updates or migrations. By default, these are omitted from the response. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [WorkflowHistoryListRequest](../schemas/Workflow/WorkflowHistoryListRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing, or the caller doesn't have permissions to perform the operation. |

**Success Response Schema:**

[WorkflowHistoryListResponseDTO](../schemas/Workflow/WorkflowHistoryListResponseDTO.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

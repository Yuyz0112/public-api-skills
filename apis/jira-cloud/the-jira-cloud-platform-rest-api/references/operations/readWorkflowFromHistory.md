# POST /rest/api/3/workflow/history

**Resource:** [Workflows](../resources/Workflows.md)
**Read workflow version from history**
**Operation ID:** `readWorkflowFromHistory`

Returns a workflow and related statuses for a specified workflow id and version number.

**Note:** Stored workflow data expires after 28 days. Additionally, no data from before the 30th of October 2025 is available.

**[Permissions](#permissions) required:**

 *  *Administer Jira* global permission to access all, including project-scoped, workflows
 *  At least one of the *Administer projects* and *View (read-only) workflow* project permissions to access project-scoped workflows

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [WorkflowHistoryReadRequest](../schemas/Workflow/WorkflowHistoryReadRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing, or the caller doesn't have permissions to perform the operation. |

**Success Response Schema:**

[WorkflowHistoryReadResponseDTO](../schemas/Workflow/WorkflowHistoryReadResponseDTO.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

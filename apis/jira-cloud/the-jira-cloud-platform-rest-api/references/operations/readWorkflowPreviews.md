# POST /rest/api/3/workflows/preview

**Resource:** [Workflows](../resources/Workflows.md)
**Preview workflow**
**Operation ID:** `readWorkflowPreviews`

Returns a requested workflow within a given project. The response provides a read-only preview of the workflow, omitting full configuration details.

**[Permissions](#permissions) required:**

 *  At least one of the *Administer projects* and *View (read-only) workflow* project permissions

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [WorkflowPreviewRequest](../schemas/Workflow/WorkflowPreviewRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing, or the caller doesn't have permissions to perform the operation. |
| 404 | Returned if one or more previews are not found. |

**Success Response Schema:**

[WorkflowPreviewResponse](../schemas/Workflow/WorkflowPreviewResponse.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

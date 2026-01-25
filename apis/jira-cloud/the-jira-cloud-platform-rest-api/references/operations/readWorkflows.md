# POST /rest/api/3/workflows

**Resource:** [Workflows](../resources/Workflows.md)
**Bulk get workflows**
**Operation ID:** `readWorkflows`

Returns a list of workflows and related statuses by providing workflow names, workflow IDs, or project and issue types.

**[Permissions](#permissions) required:**

 *  *Administer Jira* global permission to access all, including project-scoped, workflows
 *  At least one of the *Administer projects* and *View (read-only) workflow* project permissions to access project-scoped workflows

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [WorkflowReadRequest](../schemas/Workflow/WorkflowReadRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing, or the caller doesn't have permissions to perform the operation. |

**Success Response Schema:**

[WorkflowReadResponse](../schemas/Workflow/WorkflowReadResponse.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

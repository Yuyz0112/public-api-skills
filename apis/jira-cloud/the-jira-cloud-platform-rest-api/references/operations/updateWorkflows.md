# POST /rest/api/3/workflows/update

**Resource:** [Workflows](../resources/Workflows.md)
**Bulk update workflows**
**Operation ID:** `updateWorkflows`

Update workflows and related statuses.

**[Permissions](#permissions) required:**

 *  *Administer Jira* project permission to create all, including global-scoped, workflows
 *  *Administer projects* project permissions to create project-scoped workflows

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [WorkflowUpdateRequest](../schemas/Workflow/WorkflowUpdateRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing, or the caller doesn't have permissions to perform the operation. |
| 409 | Returned if another workflow configuration update task is ongoing. |

**Success Response Schema:**

[WorkflowUpdateResponse](../schemas/Workflow/WorkflowUpdateResponse.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

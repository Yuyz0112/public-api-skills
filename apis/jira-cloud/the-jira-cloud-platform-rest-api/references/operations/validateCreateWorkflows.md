# POST /rest/api/3/workflows/create/validation

**Resource:** [Workflows](../resources/Workflows.md)
**Validate create workflows**
**Operation ID:** `validateCreateWorkflows`

Validate the payload for bulk create workflows.

**[Permissions](#permissions) required:**

 *  *Administer Jira* project permission to create all, including global-scoped, workflows
 *  *Administer projects* project permissions to create project-scoped workflows

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [WorkflowCreateValidateRequest](../schemas/Workflow/WorkflowCreateValidateRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing, or the caller doesn't have permissions to perform the operation. |

**Success Response Schema:**

[WorkflowValidationErrorList](../schemas/Workflow/WorkflowValidationErrorList.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

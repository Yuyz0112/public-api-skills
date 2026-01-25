# POST /rest/api/3/workflows/update/validation

**Resource:** [Workflows](../resources/Workflows.md)
**Validate update workflows**
**Operation ID:** `validateUpdateWorkflows`

Validate the payload for bulk update workflows.

**[Permissions](#permissions) required:**

 *  *Administer Jira* project permission to create all, including global-scoped, workflows
 *  *Administer projects* project permissions to create project-scoped workflows

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [WorkflowUpdateValidateRequestBean](../schemas/Workflow/WorkflowUpdateValidateRequestBean.md)

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

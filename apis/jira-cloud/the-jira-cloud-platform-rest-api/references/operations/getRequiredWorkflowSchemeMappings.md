# POST /rest/api/3/workflowscheme/update/mappings

**Resource:** [Workflow schemes](../resources/Workflow-schemes.md)
**Get required status mappings for workflow scheme update**
**Operation ID:** `getRequiredWorkflowSchemeMappings`

Gets the required status mappings for the desired changes to a workflow scheme. The results are provided per issue type and workflow. When updating a workflow scheme, status mappings can be provided per issue type, per workflow, or both.

**[Permissions](#permissions) required:**

 *  *Administer Jira* permission to update all, including global-scoped, workflow schemes.
 *  *Administer projects* project permission to update project-scoped workflow schemes.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [WorkflowSchemeUpdateRequiredMappingsRequest](../schemas/Workflow/WorkflowSchemeUpdateRequiredMappingsRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing, or the caller doesn't have permissions to perform the operation. |

**Success Response Schema:**

[WorkflowSchemeUpdateRequiredMappingsResponse](../schemas/Workflow/WorkflowSchemeUpdateRequiredMappingsResponse.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

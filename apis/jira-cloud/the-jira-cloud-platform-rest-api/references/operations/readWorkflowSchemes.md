# POST /rest/api/3/workflowscheme/read

**Resource:** [Workflow schemes](../resources/Workflow-schemes.md)
**Bulk get workflow schemes**
**Operation ID:** `readWorkflowSchemes`

Returns a list of workflow schemes by providing workflow scheme IDs or project IDs.

**[Permissions](#permissions) required:**

 *  *Administer Jira* global permission to access all, including project-scoped, workflow schemes
 *  *Administer projects* project permissions to access project-scoped workflow schemes

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [WorkflowSchemeReadRequest](../schemas/Workflow/WorkflowSchemeReadRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing, or the caller doesn't have permissions to perform the operation. |

**Success Response Schema:**

Array of [WorkflowSchemeReadResponse](../schemas/Workflow/WorkflowSchemeReadResponse.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

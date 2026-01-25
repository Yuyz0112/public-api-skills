# POST /rest/api/3/workflowscheme/update

**Resource:** [Workflow schemes](../resources/Workflow-schemes.md)
**Update workflow scheme**
**Operation ID:** `updateSchemes`

Updates company-managed and team-managed project workflow schemes. This API doesn't have a concept of draft, so any changes made to a workflow scheme are immediately available. When changing the available statuses for issue types, an [asynchronous task](#async) migrates the issues as defined in the provided mappings.

**[Permissions](#permissions) required:**

 *  *Administer Jira* project permission to update all, including global-scoped, workflow schemes.
 *  *Administer projects* project permission to update project-scoped workflow schemes.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [WorkflowSchemeUpdateRequest](../schemas/Workflow/WorkflowSchemeUpdateRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful and there is no asynchronous task. |
| 303 | Returned if the request is successful and there is an asynchronous task for the migrations. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing, or the caller doesn't have permissions to perform the operation. |
| 409 | Returned if another workflow configuration update task is ongoing. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

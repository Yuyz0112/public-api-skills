# POST /rest/api/3/workflowscheme/project/switch

**Resource:** [Workflow schemes](../resources/Workflow-schemes.md)
**Switch workflow scheme for project**
**Operation ID:** `switchWorkflowSchemeForProject`

Switches a workflow scheme for a project.

Workflow schemes can only be assigned to classic projects.

**Calculating required mappings:** If statuses from the current workflow scheme won't exist in the target workflow scheme, you must provide `mappingsByIssueTypeOverride` to specify how issues with those statuses should be migrated. Use [the required workflow scheme mappings API](#api-rest-api-3-workflowscheme-update-mappings-post) to determine which statuses and issue types require mappings.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Request Body

The request containing project ID, target scheme ID, and any issue type mappings.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [WorkflowSchemeProjectSwitchBean](../schemas/Workflow/WorkflowSchemeProjectSwitchBean.md)

## Responses

| Status | Description |
|--------|-------------|
| 303 | Returned if the request is successful and the task has been started. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing, or the caller doesn't have permissions to perform the operation. |
| 409 | Returned if another workflow scheme switch task is already running. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

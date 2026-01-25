# DELETE /rest/api/3/workflowscheme/{id}/draft/default

**Resource:** [Workflow scheme drafts](../resources/Workflow-scheme-drafts.md)
**Delete draft default workflow**
**Operation ID:** `deleteDraftDefaultWorkflow`

Resets the default workflow for a workflow scheme's draft. That is, the default workflow is set to Jira's system workflow (the *jira* workflow).

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer (int64) | Yes | The ID of the workflow scheme that the draft belongs to. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if any of the following is true:

 *  The workflow scheme is not found.
 *  The workflow scheme does not have a draft. |

**Success Response Schema:**

[WorkflowScheme](../schemas/Workflow/WorkflowScheme.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

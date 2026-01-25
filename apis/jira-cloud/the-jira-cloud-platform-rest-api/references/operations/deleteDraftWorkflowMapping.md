# DELETE /rest/api/3/workflowscheme/{id}/draft/workflow

**Resource:** [Workflow scheme drafts](../resources/Workflow-scheme-drafts.md)
**Delete issue types for workflow in draft workflow scheme**
**Operation ID:** `deleteDraftWorkflowMapping`

Deletes the workflow-issue type mapping for a workflow in a workflow scheme's draft.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer (int64) | Yes | The ID of the workflow scheme that the draft belongs to. |
| `workflowName` | query | string | Yes | The name of the workflow. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if any of the following is true:

 *  The workflow scheme is not found.
 *  The workflow scheme does not have a draft.
 *  The workflow is not found.
 *  The workflow is not specified. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

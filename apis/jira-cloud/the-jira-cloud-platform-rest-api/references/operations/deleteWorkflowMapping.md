# DELETE /rest/api/3/workflowscheme/{id}/workflow

**Resource:** [Workflow schemes](../resources/Workflow-schemes.md)
**Delete issue types for workflow in workflow scheme**
**Operation ID:** `deleteWorkflowMapping`

Deletes the workflow-issue type mapping for a workflow in a workflow scheme.

Note that active workflow schemes cannot be edited. If the workflow scheme is active, set `updateDraftIfNeeded` to `true` and a draft workflow scheme is created or updated with the workflow-issue type mapping deleted. The draft workflow scheme can be published in Jira.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer (int64) | Yes | The ID of the workflow scheme. |
| `workflowName` | query | string | Yes | The name of the workflow. |
| `updateDraftIfNeeded` | query | boolean | No | Set to true to create or update the draft of a workflow scheme and delete the mapping from the draft, when the workflow scheme cannot be edited. Defaults to `false`. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the workflow cannot be edited and `updateDraftIfNeeded` is not true. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if any of the following is true:

 *  The workflow scheme is not found.
 *  The workflow is not found.
 *  The workflow is not specified. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

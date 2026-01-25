# PUT /rest/api/3/workflowscheme/{id}/workflow

**Resource:** [Workflow schemes](../resources/Workflow-schemes.md)
**Set issue types for workflow in workflow scheme**
**Operation ID:** `updateWorkflowMapping`

Sets the issue types for a workflow in a workflow scheme. The workflow can also be set as the default workflow for the workflow scheme. Unmapped issues types are mapped to the default workflow.

Note that active workflow schemes cannot be edited. If the workflow scheme is active, set `updateDraftIfNeeded` to `true` in the request body and a draft workflow scheme is created or updated with the new workflow-issue types mappings. The draft workflow scheme can be published in Jira.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer (int64) | Yes | The ID of the workflow scheme. |
| `workflowName` | query | string | Yes | The name of the workflow. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [IssueTypesWorkflowMapping](../schemas/Issue/IssueTypesWorkflowMapping.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if any of the following is true:

 *  The workflow scheme is not found.
 *  The workflow is not found.
 *  The workflow is not specified. |

**Success Response Schema:**

[WorkflowScheme](../schemas/Workflow/WorkflowScheme.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

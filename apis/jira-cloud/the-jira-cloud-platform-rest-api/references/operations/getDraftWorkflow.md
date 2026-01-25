# GET /rest/api/3/workflowscheme/{id}/draft/workflow

**Resource:** [Workflow scheme drafts](../resources/Workflow-scheme-drafts.md)
**Get issue types for workflows in draft workflow scheme**
**Operation ID:** `getDraftWorkflow`

Returns the workflow-issue type mappings for a workflow scheme's draft.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer (int64) | Yes | The ID of the workflow scheme that the draft belongs to. |
| `workflowName` | query | string | No | The name of a workflow in the scheme. Limits the results to the workflow-issue type mapping for the specified workflow. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if either the workflow scheme or workflow (if specified) is not found. session. |

**Success Response Schema:**

[IssueTypesWorkflowMapping](../schemas/Issue/IssueTypesWorkflowMapping.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

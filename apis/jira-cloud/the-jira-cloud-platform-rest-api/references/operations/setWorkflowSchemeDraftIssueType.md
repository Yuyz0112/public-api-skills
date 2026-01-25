# PUT /rest/api/3/workflowscheme/{id}/draft/issuetype/{issueType}

**Resource:** [Workflow scheme drafts](../resources/Workflow-scheme-drafts.md)
**Set workflow for issue type in draft workflow scheme**
**Operation ID:** `setWorkflowSchemeDraftIssueType`

Sets the workflow for an issue type in a workflow scheme's draft.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer (int64) | Yes | The ID of the workflow scheme that the draft belongs to. |
| `issueType` | path | string | Yes | The ID of the issue type. |

## Request Body

The issue type-project mapping.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [IssueTypeWorkflowMapping](../schemas/Issue/IssueTypeWorkflowMapping.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if the workflow scheme or issue type is not found. |

**Success Response Schema:**

[WorkflowScheme](../schemas/Workflow/WorkflowScheme.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

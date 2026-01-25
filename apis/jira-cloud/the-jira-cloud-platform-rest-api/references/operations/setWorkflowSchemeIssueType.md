# PUT /rest/api/3/workflowscheme/{id}/issuetype/{issueType}

**Resource:** [Workflow schemes](../resources/Workflow-schemes.md)
**Set workflow for issue type in workflow scheme**
**Operation ID:** `setWorkflowSchemeIssueType`

Sets the workflow for an issue type in a workflow scheme.

Note that active workflow schemes cannot be edited. If the workflow scheme is active, set `updateDraftIfNeeded` to `true` in the request body and a draft workflow scheme is created or updated with the new issue type-workflow mapping. The draft workflow scheme can be published in Jira.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer (int64) | Yes | The ID of the workflow scheme. |
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
| 400 | Returned if the workflow cannot be edited and `updateDraftIfNeeded` is false. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if the workflow scheme or issue type is not found. |

**Success Response Schema:**

[WorkflowScheme](../schemas/Workflow/WorkflowScheme.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

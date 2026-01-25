# GET /rest/api/3/workflowscheme/{id}/issuetype/{issueType}

**Resource:** [Workflow schemes](../resources/Workflow-schemes.md)
**Get workflow for issue type in workflow scheme**
**Operation ID:** `getWorkflowSchemeIssueType`

Returns the issue type-workflow mapping for an issue type in a workflow scheme.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer (int64) | Yes | The ID of the workflow scheme. |
| `issueType` | path | string | Yes | The ID of the issue type. |
| `returnDraftIfExists` | query | boolean | No | Returns the mapping from the workflow scheme's draft rather than the workflow scheme, if set to true. If no draft exists, the mapping from the workflow scheme is returned. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if the workflow scheme or issue type is not found. |

**Success Response Schema:**

[IssueTypeWorkflowMapping](../schemas/Issue/IssueTypeWorkflowMapping.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

# GET /rest/api/3/workflowscheme/{id}/workflow

**Resource:** [Workflow schemes](../resources/Workflow-schemes.md)
**Get issue types for workflows in workflow scheme**
**Operation ID:** `getWorkflow`

Returns the workflow-issue type mappings for a workflow scheme.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer (int64) | Yes | The ID of the workflow scheme. |
| `workflowName` | query | string | No | The name of a workflow in the scheme. Limits the results to the workflow-issue type mapping for the specified workflow. |
| `returnDraftIfExists` | query | boolean | No | Returns the mapping from the workflow scheme's draft rather than the workflow scheme, if set to true. If no draft exists, the mapping from the workflow scheme is returned. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if either the workflow scheme or workflow is not found. |

**Success Response Schema:**

[IssueTypesWorkflowMapping](../schemas/Issue/IssueTypesWorkflowMapping.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

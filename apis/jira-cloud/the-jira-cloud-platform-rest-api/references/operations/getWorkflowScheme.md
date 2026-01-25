# GET /rest/api/3/workflowscheme/{id}

**Resource:** [Workflow schemes](../resources/Workflow-schemes.md)
**Get workflow scheme**
**Operation ID:** `getWorkflowScheme`

Returns a workflow scheme.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer (int64) | Yes | The ID of the workflow scheme. Find this ID by editing the desired workflow scheme in Jira. The ID is shown in the URL as `schemeId`. For example, *schemeId=10301*. |
| `returnDraftIfExists` | query | boolean | No | Returns the workflow scheme's draft rather than scheme itself, if set to true. If the workflow scheme does not have a draft, then the workflow scheme is returned. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if the workflow scheme is not found. |

**Success Response Schema:**

[WorkflowScheme](../schemas/Workflow/WorkflowScheme.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

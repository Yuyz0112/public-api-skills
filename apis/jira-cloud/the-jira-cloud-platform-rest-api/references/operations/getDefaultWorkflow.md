# GET /rest/api/3/workflowscheme/{id}/default

**Resource:** [Workflow schemes](../resources/Workflow-schemes.md)
**Get default workflow**
**Operation ID:** `getDefaultWorkflow`

Returns the default workflow for a workflow scheme. The default workflow is the workflow that is assigned any issue types that have not been mapped to any other workflow. The default workflow has *All Unassigned Issue Types* listed in its issue types for the workflow scheme in Jira.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer (int64) | Yes | The ID of the workflow scheme. |
| `returnDraftIfExists` | query | boolean | No | Set to `true` to return the default workflow for the workflow scheme's draft rather than scheme itself. If the workflow scheme does not have a draft, then the default workflow for the workflow scheme is returned. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if the workflow scheme is not found. |

**Success Response Schema:**

[DefaultWorkflow](../schemas/Default/DefaultWorkflow.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

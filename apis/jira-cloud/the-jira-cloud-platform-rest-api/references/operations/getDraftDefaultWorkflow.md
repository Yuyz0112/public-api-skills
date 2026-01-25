# GET /rest/api/3/workflowscheme/{id}/draft/default

**Resource:** [Workflow scheme drafts](../resources/Workflow-scheme-drafts.md)
**Get draft default workflow**
**Operation ID:** `getDraftDefaultWorkflow`

Returns the default workflow for a workflow scheme's draft. The default workflow is the workflow that is assigned any issue types that have not been mapped to any other workflow. The default workflow has *All Unassigned Issue Types* listed in its issue types for the workflow scheme in Jira.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer (int64) | Yes | The ID of the workflow scheme that the draft belongs to. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission.. |
| 404 | Returned if any of the following is true:

 *  The workflow scheme is not found.
 *  The workflow scheme does not have a draft. |

**Success Response Schema:**

[DefaultWorkflow](../schemas/Default/DefaultWorkflow.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

# PUT /rest/api/3/workflowscheme/{id}/default

**Resource:** [Workflow schemes](../resources/Workflow-schemes.md)
**Update default workflow**
**Operation ID:** `updateDefaultWorkflow`

Sets the default workflow for a workflow scheme.

Note that active workflow schemes cannot be edited. If the workflow scheme is active, set `updateDraftIfNeeded` to `true` in the request object and a draft workflow scheme is created or updated with the new default workflow. The draft workflow scheme can be published in Jira.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer (int64) | Yes | The ID of the workflow scheme. |

## Request Body

The new default workflow.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [DefaultWorkflow](../schemas/Default/DefaultWorkflow.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the workflow scheme cannot be edited and `updateDraftIfNeeded` is not `true`. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if the workflow scheme is not found. |

**Success Response Schema:**

[WorkflowScheme](../schemas/Workflow/WorkflowScheme.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

# PUT /rest/api/3/workflowscheme/{id}/draft

**Resource:** [Workflow scheme drafts](../resources/Workflow-scheme-drafts.md)
**Update draft workflow scheme**
**Operation ID:** `updateWorkflowSchemeDraft`

Updates a draft workflow scheme. If a draft workflow scheme does not exist for the active workflow scheme, then a draft is created. Note that an active workflow scheme can only have one draft workflow scheme.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer (int64) | Yes | The ID of the active workflow scheme that the draft was created from. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [WorkflowScheme](../schemas/Workflow/WorkflowScheme.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if:

 *  the original active workflow scheme is not found.
 *  the original active workflow scheme does not have a draft. |

**Success Response Schema:**

[WorkflowScheme](../schemas/Workflow/WorkflowScheme.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

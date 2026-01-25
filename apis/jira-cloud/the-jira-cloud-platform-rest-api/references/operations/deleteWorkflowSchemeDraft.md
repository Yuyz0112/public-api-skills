# DELETE /rest/api/3/workflowscheme/{id}/draft

**Resource:** [Workflow scheme drafts](../resources/Workflow-scheme-drafts.md)
**Delete draft workflow scheme**
**Operation ID:** `deleteWorkflowSchemeDraft`

Deletes a draft workflow scheme.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer (int64) | Yes | The ID of the active workflow scheme that the draft was created from. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission.. |
| 404 | Returned if:

 *  the original active workflow scheme is not found.
 *  the original active workflow scheme does not have a draft. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

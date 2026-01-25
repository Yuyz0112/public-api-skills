# GET /rest/api/3/workflowscheme/{id}/draft

**Resource:** [Workflow scheme drafts](../resources/Workflow-scheme-drafts.md)
**Get draft workflow scheme**
**Operation ID:** `getWorkflowSchemeDraft`

Returns the draft workflow scheme for an active workflow scheme. Draft workflow schemes allow changes to be made to the active workflow schemes: When an active workflow scheme is updated, a draft copy is created. The draft is modified, then the changes in the draft are copied back to the active workflow scheme. See [Configuring workflow schemes](https://confluence.atlassian.com/x/tohKLg) for more information.  
Note that:

 *  Only active workflow schemes can have draft workflow schemes.
 *  An active workflow scheme can only have one draft workflow scheme.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer (int64) | Yes | The ID of the active workflow scheme that the draft was created from. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
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

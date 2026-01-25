# POST /rest/api/3/workflowscheme/{id}/draft/publish

**Resource:** [Workflow scheme drafts](../resources/Workflow-scheme-drafts.md)
**Publish draft workflow scheme**
**Operation ID:** `publishDraftWorkflowScheme`

Publishes a draft workflow scheme.

Where the draft workflow includes new workflow statuses for an issue type, mappings are provided to update issues with the original workflow status to the new workflow status.

This operation is [asynchronous](#async). Follow the `location` link in the response to determine the status of the task and use [Get task](#api-rest-api-3-task-taskId-get) to obtain updates.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer (int64) | Yes | The ID of the workflow scheme that the draft belongs to. |
| `validateOnly` | query | boolean | No | Whether the request only performs a validation. |

## Request Body

Details of the status mappings.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [PublishDraftWorkflowScheme](../schemas/Publish/PublishDraftWorkflowScheme.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is only for validation and is successful. |
| 303 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if any of these are true:

 *  The workflow scheme is not found.
 *  The workflow scheme does not have a draft.
 *  A new status in the draft workflow scheme is not found. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

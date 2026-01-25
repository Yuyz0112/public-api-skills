# DELETE /rest/api/3/workflow/{entityId}

**Resource:** [Workflows](../resources/Workflows.md)
**Delete inactive workflow**
**Operation ID:** `deleteInactiveWorkflow`

Deletes a workflow.

The workflow cannot be deleted if it is:

 *  an active workflow.
 *  a system workflow.
 *  associated with any workflow scheme.
 *  associated with any draft workflow scheme.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `entityId` | path | string | Yes | The entity ID of the workflow. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the workflow is deleted. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the required permissions. |
| 404 | Returned if the workflow is not found. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration

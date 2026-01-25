# GET /rest/api/3/status/{idOrName}

**Resource:** [Workflow statuses](../resources/Workflow-statuses.md)
**Get status**
**Operation ID:** `getStatus`

Returns a status. The status must be associated with an active workflow to be returned.

If a name is used on more than one status, only the status found first is returned. Therefore, identifying the status by its ID may be preferable.

This operation can be accessed anonymously.

[Permissions](#permissions) required: *Browse projects* [project permission](https://support.atlassian.com/jira-cloud-administration/docs/manage-project-permissions/) for the project.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `idOrName` | path | string | Yes | The ID or name of the status. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if:

 *  the status is not found.
 *  the status is not associated with a workflow.
 *  the user does not have the required permissions. |

**Success Response Schema:**

[StatusDetails](../schemas/Status/StatusDetails.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work

# GET /rest/api/3/status

**Resource:** [Workflow statuses](../resources/Workflow-statuses.md)
**Get all statuses**
**Operation ID:** `getStatuses`

Returns a list of all statuses associated with active workflows.

This operation can be accessed anonymously.

[Permissions](#permissions) required: *Browse projects* [project permission](https://support.atlassian.com/jira-cloud-administration/docs/manage-project-permissions/) for the project.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |

**Success Response Schema:**

Array of [StatusDetails](../schemas/Status/StatusDetails.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work

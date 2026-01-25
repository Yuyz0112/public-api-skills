# GET /rest/api/3/statuscategory

**Resource:** [Workflow status categories](../resources/Workflow-status-categories.md)
**Get all status categories**
**Operation ID:** `getStatusCategories`

Returns a list of all status categories.

**[Permissions](#permissions) required:** Permission to access Jira.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |

**Success Response Schema:**

Array of [StatusCategory](../schemas/Status/StatusCategory.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work

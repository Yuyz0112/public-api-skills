# DELETE /rest/api/3/dashboard/{id}

**Resource:** [Dashboards](../resources/Dashboards.md)
**Delete dashboard**
**Operation ID:** `deleteDashboard`

Deletes a dashboard.

**[Permissions](#permissions) required:** None

The dashboard to be deleted must be owned by the user.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of the dashboard. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the dashboard is deleted. |
| 400 | 400 response |
| 401 | Returned if the authentication credentials are incorrect or missing. |

## Security

- **basicAuth**
- **OAuth2**: write:jira-work

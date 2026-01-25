# GET /rest/api/3/dashboard/{id}

**Resource:** [Dashboards](../resources/Dashboards.md)
**Get dashboard**
**Operation ID:** `getDashboard`

Returns a dashboard.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** None.

However, to get a dashboard, the dashboard must be shared with the user or the user must own it. Note, users with the *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg) are considered owners of the System dashboard. The System dashboard is considered to be shared with all other users.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of the dashboard. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | 400 response |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if the dashboard is not found or the dashboard is not owned by or shared with the user. |

**Success Response Schema:**

[Dashboard](../schemas/Dashboard/Dashboard.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work

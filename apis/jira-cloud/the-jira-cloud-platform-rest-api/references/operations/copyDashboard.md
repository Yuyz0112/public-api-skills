# POST /rest/api/3/dashboard/{id}/copy

**Resource:** [Dashboards](../resources/Dashboards.md)
**Copy dashboard**
**Operation ID:** `copyDashboard`

Copies a dashboard. Any values provided in the `dashboard` parameter replace those in the copied dashboard.

**[Permissions](#permissions) required:** None

The dashboard to be copied must be owned by or shared with the user.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes |  |
| `extendAdminPermissions` | query | boolean | No | Whether admin level permissions are used. It should only be true if the user has *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg) |

## Request Body

Dashboard details.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [DashboardDetails](../schemas/Dashboard/DashboardDetails.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if the dashboard is not found or the dashboard is not owned by or shared with the user. |

**Success Response Schema:**

[Dashboard](../schemas/Dashboard/Dashboard.md)

## Security

- **basicAuth**
- **OAuth2**: write:jira-work

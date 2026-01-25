# PUT /rest/api/3/dashboard/{id}

**Resource:** [Dashboards](../resources/Dashboards.md)
**Update dashboard**
**Operation ID:** `updateDashboard`

Updates a dashboard, replacing all the dashboard details with those provided.

**[Permissions](#permissions) required:** None

The dashboard to be updated must be owned by the user.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of the dashboard to update. |
| `extendAdminPermissions` | query | boolean | No | Whether admin level permissions are used. It should only be true if the user has *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg) |

## Request Body

Replacement dashboard details.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [DashboardDetails](../schemas/Dashboard/DashboardDetails.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if the dashboard is not found or the dashboard is not owned by the user. |

**Success Response Schema:**

[Dashboard](../schemas/Dashboard/Dashboard.md)

## Security

- **basicAuth**
- **OAuth2**: write:jira-work

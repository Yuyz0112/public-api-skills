# POST /rest/api/3/dashboard

**Resource:** [Dashboards](../resources/Dashboards.md)
**Create dashboard**
**Operation ID:** `createDashboard`

Creates a dashboard.

**[Permissions](#permissions) required:** None.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
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

**Success Response Schema:**

[Dashboard](../schemas/Dashboard/Dashboard.md)

## Security

- **basicAuth**
- **OAuth2**: write:jira-work

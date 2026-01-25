# GET /projects/{project_gid}/project_statuses

**Resource:** [Project statuses](../resources/Project-statuses.md)
**Get statuses from a project**
**Operation ID:** `getProjectStatusesForProject`

*Deprecated: new integrations should prefer the `/status_updates` route.*

Returns the compact project status update records for all updates on the project.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved the specified project's status updates. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**

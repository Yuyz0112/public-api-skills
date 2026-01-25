# GET /project_statuses/{project_status_gid}

**Resource:** [Project statuses](../resources/Project-statuses.md)
**Get a project status**
**Operation ID:** `getProjectStatus`

*Deprecated: new integrations should prefer the `/status_updates/{status_gid}` route.*

Returns the complete record for a single status update.

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

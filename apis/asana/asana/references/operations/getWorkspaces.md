# GET /workspaces

**Resource:** [Workspaces](../resources/Workspaces.md)
**Get multiple workspaces**
**Operation ID:** `getWorkspaces`

<b>Required scope: </b><code>workspaces:read</code>

Returns the compact records for all workspaces visible to the authorized user.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Return all workspaces visible to the authorized user. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: workspaces:read

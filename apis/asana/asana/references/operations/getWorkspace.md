# GET /workspaces/{workspace_gid}

**Resource:** [Workspaces](../resources/Workspaces.md)
**Get a workspace**
**Operation ID:** `getWorkspace`

<b>Required scope: </b><code>workspaces:read</code>

Returns the full workspace record for a single workspace.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Return the full workspace record. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: workspaces:read

# GET /workspaces/{workspace_gid}/workspace_memberships

**Resource:** [Workspace memberships](../resources/Workspace-memberships.md)
**Get the workspace memberships for a workspace**
**Operation ID:** `getWorkspaceMembershipsForWorkspace`

Returns the compact workspace membership records for the workspace.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved the requested workspace's memberships. |

## Security

- **personalAccessToken**
- **oauth2**

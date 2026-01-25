# POST /workspaces/{workspace_gid}/addUser

**Resource:** [Workspaces](../resources/Workspaces.md)
**Add a user to a workspace or organization**
**Operation ID:** `addUserForWorkspace`

Add a user to a workspace or organization.
The user can be referenced by their globally unique user ID or their email address. Returns the full user record for the invited user.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Request Body

The user to add to the workspace.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | The user was added successfully to the workspace or organization. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**

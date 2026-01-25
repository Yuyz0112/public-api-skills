# POST /workspaces/{workspace_gid}/projects

**Resource:** [Projects](../resources/Projects.md)
**Create a project in a workspace**
**Operation ID:** `createProjectForWorkspace`

<b>Required scope: </b><code>projects:write</code>

Creates a project in the workspace.

If the workspace for your project is an organization, you must also
supply a team to share the project with.

Returns the full record of the newly created project.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Request Body

The new project to create.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Successfully created a new project in the specified workspace. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: projects:write

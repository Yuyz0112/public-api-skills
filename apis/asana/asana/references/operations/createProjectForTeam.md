# POST /teams/{team_gid}/projects

**Resource:** [Projects](../resources/Projects.md)
**Create a project in a team**
**Operation ID:** `createProjectForTeam`

<b>Required scope: </b><code>projects:write</code>

Creates a project shared with the given team.

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
| 201 | Successfully created the specified project. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: projects:write

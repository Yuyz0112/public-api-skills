# POST /projects

**Resource:** [Projects](../resources/Projects.md)
**Create a project**
**Operation ID:** `createProject`

<b>Required scope: </b><code>projects:write</code>

Create a new project in a workspace or team.

Every project is required to be created in a specific workspace or
organization, and this cannot be changed once set. Note that you can use
the `workspace` parameter regardless of whether or not it is an
organization.

If the workspace for your project is an organization, you must also
supply a `team` to share the project with.

Returns the full record of the newly created project.

**Deprecation notice:** The `team` parameter and the `private_to_team`
value for `privacy_setting` are deprecated. When either is included in
the request, the `Asana-Change` response header will indicate an affected
deprecation. Clients should switch to using `POST /memberships` with
`{ parent: project, member: team }` to share a project with a team after
creation.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Request Body

The project to create.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Successfully retrieved projects. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: projects:write

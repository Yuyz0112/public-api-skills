# PUT /projects/{project_gid}

**Resource:** [Projects](../resources/Projects.md)
**Update a project**
**Operation ID:** `updateProject`

<b>Required scope: </b><code>projects:write</code>

A specific, existing project can be updated by making a PUT request on
the URL for that project. Only the fields provided in the `data` block
will be updated; any unspecified fields will remain unchanged.

When using this method, it is best to specify only those fields you wish
to change, or else you may overwrite changes made by another user since
you last retrieved the task.

Returns the complete updated project record.

**Deprecation notice:** Updating the `team` field is deprecated. When this
field is included in the request, the `Asana-Change` response header will
indicate an affected deprecation. Clients should switch to using
`POST /memberships` with `{ parent: project, member: team }` to share a
project with a team.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Request Body

The updated fields for the project.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully updated the project. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: projects:write

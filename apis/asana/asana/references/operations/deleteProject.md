# DELETE /projects/{project_gid}

**Resource:** [Projects](../resources/Projects.md)
**Delete a project**
**Operation ID:** `deleteProject`

<b>Required scope: </b><code>projects:delete</code>

A specific, existing project can be deleted by making a DELETE request on
the URL for that project.

Returns an empty data record.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully deleted the specified project. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: projects:delete

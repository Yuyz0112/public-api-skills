# DELETE /project_statuses/{project_status_gid}

**Resource:** [Project statuses](../resources/Project-statuses.md)
**Delete a project status**
**Operation ID:** `deleteProjectStatus`

*Deprecated: new integrations should prefer the `/status_updates/{status_gid}` route.*

Deletes a specific, existing project status update.

Returns an empty data record.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully deleted the specified project status. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**

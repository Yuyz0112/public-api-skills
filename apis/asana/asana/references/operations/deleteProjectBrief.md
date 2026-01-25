# DELETE /project_briefs/{project_brief_gid}

**Resource:** [Project briefs](../resources/Project-briefs.md)
**Delete a project brief**
**Operation ID:** `deleteProjectBrief`

Deletes a specific, existing project brief.

Returns an empty data record.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully deleted the specified project brief. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**

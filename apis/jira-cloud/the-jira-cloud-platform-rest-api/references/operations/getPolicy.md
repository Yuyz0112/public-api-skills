# GET /rest/api/3/data-policy

**Resource:** [App data policies](../resources/App-data-policies.md)
**Get data policy for the workspace**
**Operation ID:** `getPolicy`

Returns data policy for the workspace.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the client is not authorized to make the request. |

**Success Response Schema:**

[WorkspaceDataPolicy](../schemas/Workspace/WorkspaceDataPolicy.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work

# PUT /user/installations/{installation_id}/repositories/{repository_id}

**Resource:** [apps](../resources/apps.md)
**Add a repository to an app installation**
**Operation ID:** `apps/add-repo-to-installation-for-authenticated-user`

Add a single repository to an installation. The authenticated user must have admin access to the repository.    

This endpoint only works for PATs (classic) with the `repo` scope.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 304 | (reference) |
| 403 | (reference) |
| 404 | (reference) |


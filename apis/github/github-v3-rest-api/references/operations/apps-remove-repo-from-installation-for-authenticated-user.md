# DELETE /user/installations/{installation_id}/repositories/{repository_id}

**Resource:** [apps](../resources/apps.md)
**Remove a repository from an app installation**
**Operation ID:** `apps/remove-repo-from-installation-for-authenticated-user`

Remove a single repository from an installation. The authenticated user must have admin access to the repository. The installation must have the `repository_selection` of `selected`. 

This endpoint only works for PATs (classic) with the `repo` scope.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 304 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 422 | Returned when the application is installed on `all` repositories in the organization, or if this request would remove the last repository that the application has access to in the organization. |


# DELETE /user/migrations/{migration_id}/repos/{repo_name}/lock

**Resource:** [migrations](../resources/migrations.md)
**Unlock a user repository**
**Operation ID:** `migrations/unlock-repo-for-authenticated-user`

Unlocks a repository. You can lock repositories when you [start a user migration](https://docs.github.com/rest/migrations/users#start-a-user-migration). Once the migration is complete you can unlock each repository to begin using it again or [delete the repository](https://docs.github.com/rest/repos/repos#delete-a-repository) if you no longer need the source data. Returns a status of `404 Not Found` if the repository is not locked.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |


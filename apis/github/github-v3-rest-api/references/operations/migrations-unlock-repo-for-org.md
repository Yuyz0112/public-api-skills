# DELETE /orgs/{org}/migrations/{migration_id}/repos/{repo_name}/lock

**Resource:** [migrations](../resources/migrations.md)
**Unlock an organization repository**
**Operation ID:** `migrations/unlock-repo-for-org`

Unlocks a repository that was locked for migration. You should unlock each migrated repository and [delete them](https://docs.github.com/rest/repos/repos#delete-a-repository) when the migration is complete and you no longer need the source data.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 404 | (reference) |


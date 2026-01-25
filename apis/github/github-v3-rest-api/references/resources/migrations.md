# migrations

Move projects to or from GitHub.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/orgs/{org}/migrations` | List organization migrations | [View](../operations/migrations-list-for-org.md) |
| POST | `/orgs/{org}/migrations` | Start an organization migration | [View](../operations/migrations-start-for-org.md) |
| GET | `/orgs/{org}/migrations/{migration_id}` | Get an organization migration status | [View](../operations/migrations-get-status-for-org.md) |
| GET | `/orgs/{org}/migrations/{migration_id}/archive` | Download an organization migration archive | [View](../operations/migrations-download-archive-for-org.md) |
| DELETE | `/orgs/{org}/migrations/{migration_id}/archive` | Delete an organization migration archive | [View](../operations/migrations-delete-archive-for-org.md) |
| DELETE | `/orgs/{org}/migrations/{migration_id}/repos/{repo_name}/lock` | Unlock an organization repository | [View](../operations/migrations-unlock-repo-for-org.md) |
| GET | `/orgs/{org}/migrations/{migration_id}/repositories` | List repositories in an organization migration | [View](../operations/migrations-list-repos-for-org.md) |
| GET | `/repos/{owner}/{repo}/import` | Get an import status | [View](../operations/migrations-get-import-status.md) |
| PUT | `/repos/{owner}/{repo}/import` | Start an import | [View](../operations/migrations-start-import.md) |
| DELETE | `/repos/{owner}/{repo}/import` | Cancel an import | [View](../operations/migrations-cancel-import.md) |
| PATCH | `/repos/{owner}/{repo}/import` | Update an import | [View](../operations/migrations-update-import.md) |
| GET | `/repos/{owner}/{repo}/import/authors` | Get commit authors | [View](../operations/migrations-get-commit-authors.md) |
| PATCH | `/repos/{owner}/{repo}/import/authors/{author_id}` | Map a commit author | [View](../operations/migrations-map-commit-author.md) |
| GET | `/repos/{owner}/{repo}/import/large_files` | Get large files | [View](../operations/migrations-get-large-files.md) |
| PATCH | `/repos/{owner}/{repo}/import/lfs` | Update Git LFS preference | [View](../operations/migrations-set-lfs-preference.md) |
| GET | `/user/migrations` | List user migrations | [View](../operations/migrations-list-for-authenticated-user.md) |
| POST | `/user/migrations` | Start a user migration | [View](../operations/migrations-start-for-authenticated-user.md) |
| GET | `/user/migrations/{migration_id}` | Get a user migration status | [View](../operations/migrations-get-status-for-authenticated-user.md) |
| GET | `/user/migrations/{migration_id}/archive` | Download a user migration archive | [View](../operations/migrations-get-archive-for-authenticated-user.md) |
| DELETE | `/user/migrations/{migration_id}/archive` | Delete a user migration archive | [View](../operations/migrations-delete-archive-for-authenticated-user.md) |
| DELETE | `/user/migrations/{migration_id}/repos/{repo_name}/lock` | Unlock a user repository | [View](../operations/migrations-unlock-repo-for-authenticated-user.md) |
| GET | `/user/migrations/{migration_id}/repositories` | List repositories for a user migration | [View](../operations/migrations-list-repos-for-authenticated-user.md) |

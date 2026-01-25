# DELETE /repos/{owner}/{repo}/actions/caches

**Resource:** [actions](../resources/actions.md)
**Delete GitHub Actions caches for a repository (using a cache key)**
**Operation ID:** `actions/delete-actions-cache-by-key`

Deletes one or more GitHub Actions caches for a repository, using a complete cache key. By default, all caches that match the provided key are deleted, but you can optionally provide a Git ref to restrict deletions to caches that match both the provided key and the Git ref.

OAuth tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[actions-cache-list](../schemas/actions-cache-list/actions-cache-list.md)


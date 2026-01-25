# GET /repos/{owner}/{repo}/actions/cache/storage-limit

**Resource:** [actions](../resources/actions.md)
**Get GitHub Actions cache storage limit for a repository**
**Operation ID:** `actions/get-actions-cache-storage-limit-for-repository`

Gets GitHub Actions cache storage limit for a repository. This determines the maximum size of caches that can be
stored before eviction occurs.

OAuth tokens and personal access tokens (classic) need the `admin:repository` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[actions-cache-storage-limit-for-repository](../schemas/actions-cache-storage-limit-for-repository/actions-cache-storage-limit-for-repository.md)


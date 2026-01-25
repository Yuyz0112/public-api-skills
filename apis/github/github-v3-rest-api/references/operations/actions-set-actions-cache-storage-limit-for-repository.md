# PUT /repos/{owner}/{repo}/actions/cache/storage-limit

**Resource:** [actions](../resources/actions.md)
**Set GitHub Actions cache storage limit for a repository**
**Operation ID:** `actions/set-actions-cache-storage-limit-for-repository`

Sets GitHub Actions cache storage limit for a repository. This determines the maximum size of caches that can be
stored before eviction occurs.

OAuth tokens and personal access tokens (classic) need the `admin:repository` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [actions-cache-storage-limit-for-repository](../schemas/actions-cache-storage-limit-for-repository/actions-cache-storage-limit-for-repository.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 400 | (reference) |
| 403 | (reference) |
| 404 | (reference) |


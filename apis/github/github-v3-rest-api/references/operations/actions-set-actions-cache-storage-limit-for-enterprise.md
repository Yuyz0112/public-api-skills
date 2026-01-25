# PUT /enterprises/{enterprise}/actions/cache/storage-limit

**Resource:** [actions](../resources/actions.md)
**Set GitHub Actions cache storage limit for an enterprise**
**Operation ID:** `actions/set-actions-cache-storage-limit-for-enterprise`

Sets GitHub Actions cache storage limit for an enterprise. All organizations and repositories under this
enterprise may not set a higher cache storage limit.

OAuth tokens and personal access tokens (classic) need the `admin:enterprise` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [actions-cache-storage-limit-for-enterprise](../schemas/actions-cache-storage-limit-for-enterprise/actions-cache-storage-limit-for-enterprise.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 400 | (reference) |
| 403 | (reference) |
| 404 | (reference) |


# GET /enterprises/{enterprise}/actions/cache/storage-limit

**Resource:** [actions](../resources/actions.md)
**Get GitHub Actions cache storage limit for an enterprise**
**Operation ID:** `actions/get-actions-cache-storage-limit-for-enterprise`

Gets GitHub Actions cache storage limit for an enterprise. All organizations and repositories under this
enterprise may not set a higher cache storage limit.

OAuth tokens and personal access tokens (classic) need the `admin:enterprise` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[actions-cache-storage-limit-for-enterprise](../schemas/actions-cache-storage-limit-for-enterprise/actions-cache-storage-limit-for-enterprise.md)


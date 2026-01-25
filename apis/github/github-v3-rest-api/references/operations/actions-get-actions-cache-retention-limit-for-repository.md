# GET /repos/{owner}/{repo}/actions/cache/retention-limit

**Resource:** [actions](../resources/actions.md)
**Get GitHub Actions cache retention limit for a repository**
**Operation ID:** `actions/get-actions-cache-retention-limit-for-repository`

Gets GitHub Actions cache retention limit for a repository. This determines how long caches will be retained for, if
not manually removed or evicted due to size constraints.

OAuth tokens and personal access tokens (classic) need the `admin:repository` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[actions-cache-retention-limit-for-repository](../schemas/actions-cache-retention-limit-for-repository/actions-cache-retention-limit-for-repository.md)


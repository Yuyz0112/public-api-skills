# PUT /repos/{owner}/{repo}/actions/cache/retention-limit

**Resource:** [actions](../resources/actions.md)
**Set GitHub Actions cache retention limit for a repository**
**Operation ID:** `actions/set-actions-cache-retention-limit-for-repository`

Sets GitHub Actions cache retention limit for a repository. This determines how long caches will be retained for, if
not manually removed or evicted due to size constraints.

OAuth tokens and personal access tokens (classic) need the `admin:repository` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [actions-cache-retention-limit-for-repository](../schemas/actions-cache-retention-limit-for-repository/actions-cache-retention-limit-for-repository.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 400 | (reference) |
| 403 | (reference) |
| 404 | (reference) |


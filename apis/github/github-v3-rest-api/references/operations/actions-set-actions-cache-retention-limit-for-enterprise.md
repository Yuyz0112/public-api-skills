# PUT /enterprises/{enterprise}/actions/cache/retention-limit

**Resource:** [actions](../resources/actions.md)
**Set GitHub Actions cache retention limit for an enterprise**
**Operation ID:** `actions/set-actions-cache-retention-limit-for-enterprise`

Sets GitHub Actions cache retention limit for an enterprise. All organizations and repositories under this
enterprise may not set a higher cache retention limit.

OAuth tokens and personal access tokens (classic) need the `admin:enterprise` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [actions-cache-retention-limit-for-enterprise](../schemas/actions-cache-retention-limit-for-enterprise/actions-cache-retention-limit-for-enterprise.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 400 | (reference) |
| 403 | (reference) |
| 404 | (reference) |


# PUT /organizations/{org}/actions/cache/retention-limit

**Resource:** [actions](../resources/actions.md)
**Set GitHub Actions cache retention limit for an organization**
**Operation ID:** `actions/set-actions-cache-retention-limit-for-organization`

Sets GitHub Actions cache retention limit for an organization. All repositories under this
organization may not set a higher cache retention limit.

OAuth tokens and personal access tokens (classic) need the `admin:organization` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [actions-cache-retention-limit-for-organization](../schemas/actions-cache-retention-limit-for-organization/actions-cache-retention-limit-for-organization.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 400 | (reference) |
| 403 | (reference) |
| 404 | (reference) |


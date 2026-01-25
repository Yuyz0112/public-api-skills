# PUT /organizations/{org}/actions/cache/storage-limit

**Resource:** [actions](../resources/actions.md)
**Set GitHub Actions cache storage limit for an organization**
**Operation ID:** `actions/set-actions-cache-storage-limit-for-organization`

Sets GitHub Actions cache storage limit for an organization. All organizations and repositories under this
organization may not set a higher cache storage limit.

OAuth tokens and personal access tokens (classic) need the `admin:organization` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [actions-cache-storage-limit-for-organization](../schemas/actions-cache-storage-limit-for-organization/actions-cache-storage-limit-for-organization.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 400 | (reference) |
| 403 | (reference) |
| 404 | (reference) |


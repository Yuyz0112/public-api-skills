# GET /organizations/{org}/actions/cache/storage-limit

**Resource:** [actions](../resources/actions.md)
**Get GitHub Actions cache storage limit for an organization**
**Operation ID:** `actions/get-actions-cache-storage-limit-for-organization`

Gets GitHub Actions cache storage limit for an organization. All repositories under this
organization may not set a higher cache storage limit.

OAuth tokens and personal access tokens (classic) need the `admin:organization` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[actions-cache-storage-limit-for-organization](../schemas/actions-cache-storage-limit-for-organization/actions-cache-storage-limit-for-organization.md)


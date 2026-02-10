# POST /api/v4/groups/{id}/-/packages/npm/-/npm/v1/security/audits/quick

**Resource:** [Packages](../resources/Packages.md)
**NPM registry quick audit endpoint**
**Operation ID:** `postApiV4GroupsIdDashPackagesNpmDashNpmV1SecurityAuditsQuick`

This feature was introduced in GitLab 15.6

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the group |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Ok |
| 307 | Temporary Redirect |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |


# POST /api/v4/projects/{id}/packages/npm/-/npm/v1/security/advisories/bulk

**Resource:** [Packages](../resources/Packages.md)
**NPM registry bulk advisory endpoint**
**Operation ID:** `postApiV4ProjectsIdPackagesNpmDashNpmV1SecurityAdvisoriesBulk`

This feature was introduced in GitLab 15.6

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Ok |
| 307 | Temporary Redirect |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |


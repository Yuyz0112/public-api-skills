# PUT /api/v4/projects/{id}/packages/npm/{package_name}/authorize

**Resource:** [Packages](../resources/Packages.md)
**Authorize NPM package upload**
**Operation ID:** `putApiV4ProjectsIdPackagesNpmPackageNameAuthorize`

This feature was introduced in GitLab 18.6

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |


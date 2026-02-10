# GET /api/v4/projects/{id}/dependency_proxy/packages/npm/*package_name/-/*file_name

**Resource:** [Dependency proxy](../resources/Dependency-proxy.md)
**Proxy the download of a NPM package tarball**
**Operation ID:** `getApiV4ProjectsIdDependencyProxyPackagesNpm*packageNameDash*fileName`

This feature was introduced in 16.11

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `package_name` | query | string | Yes | Package name |
| `file_name` | query | string | Yes | Package file name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 403 | Forbidden |
| 404 | Not Found |


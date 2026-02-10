# GET /api/v4/projects/{id}/dependency_proxy/packages/maven/*path/{file_name}

**Resource:** [Dependency proxy](../resources/Dependency-proxy.md)
**Proxy the download of a maven package file at a project level**
**Operation ID:** `getApiV4ProjectsIdDependencyProxyPackagesMaven*pathFileName`

This feature was introduced in GitLab 16.2

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `path` | query | string | Yes | Package path |
| `file_name` | path | string | Yes | Package file name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |


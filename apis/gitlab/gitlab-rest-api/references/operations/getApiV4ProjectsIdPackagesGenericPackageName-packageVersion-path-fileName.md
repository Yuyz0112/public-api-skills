# GET /api/v4/projects/{id}/packages/generic/{package_name}/*package_version/(*path/){file_name}

**Resource:** [Packages](../resources/Packages.md)
**Download package file**
**Operation ID:** `getApiV4ProjectsIdPackagesGenericPackageName*packageVersion(*path){fileName}`

This feature was introduced in GitLab 13.5

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `package_name` | path | string | Yes | Package name |
| `package_version` | query | string | Yes | Package version |
| `path` | query | string | No | File directory path |
| `file_name` | query | string | Yes | Package file name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |


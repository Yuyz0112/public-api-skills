# GET /api/v4/projects/{id}/packages/{package_id}/package_files/{package_file_id}/download

**Resource:** [Packages](../resources/Packages.md)
**Download a package file**
**Operation ID:** `getApiV4ProjectsIdPackagesPackageIdPackageFilesPackageFileIdDownload`

This feature was introduced in GitLab 18.4

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | ID or URL-encoded path of the project |
| `package_id` | path | integer | Yes | ID of a package |
| `package_file_id` | path | integer | Yes | ID of a package file |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |


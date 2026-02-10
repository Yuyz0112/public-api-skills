# DELETE /api/v4/projects/{id}/packages/{package_id}/package_files/{package_file_id}

**Resource:** [Packages](../resources/Packages.md)
**Delete a package file**
**Operation ID:** `deleteApiV4ProjectsIdPackagesPackageIdPackageFilesPackageFileId`

This feature was introduced in GitLab 13.12

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | ID or URL-encoded path of the project |
| `package_id` | path | integer | Yes | ID of a package |
| `package_file_id` | path | integer | Yes | ID of a package file |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 403 | Forbidden |
| 404 | Not found |


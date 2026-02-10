# PUT /api/v4/projects/{id}/packages/conan/v1/files/{package_name}/{package_version}/{package_username}/{package_channel}/{recipe_revision}/export/{file_name}/authorize

**Resource:** [Packages](../resources/Packages.md)
**Workhorse authorize the conan recipe file**
**Operation ID:** `putApiV4ProjectsIdPackagesConanV1FilesPackageNamePackageVersionPackageUsernamePackageChannelRecipeRevisionExportFileNameAuthorize`

This feature was introduced in GitLab 12.6

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `package_name` | path | string | Yes | Package name |
| `package_username` | path | string | Yes | Package username |
| `package_channel` | path | string | Yes | Package channel |
| `recipe_revision` | path | string | Yes | Conan Recipe Revision |
| `file_name` | path | enum: conanfile.py, conanmanifest.txt, conan_sources.tgz... | Yes | Package file name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |


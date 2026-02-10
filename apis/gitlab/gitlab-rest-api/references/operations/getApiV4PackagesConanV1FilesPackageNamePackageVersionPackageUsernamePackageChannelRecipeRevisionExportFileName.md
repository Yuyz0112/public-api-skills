# GET /api/v4/packages/conan/v1/files/{package_name}/{package_version}/{package_username}/{package_channel}/{recipe_revision}/export/{file_name}

**Resource:** [Packages](../resources/Packages.md)
**Download recipe files**
**Operation ID:** `getApiV4PackagesConanV1FilesPackageNamePackageVersionPackageUsernamePackageChannelRecipeRevisionExportFileName`

This feature was introduced in GitLab 12.6

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `package_name` | path | string | Yes | Package name |
| `package_version` | query | string | Yes | Package version |
| `package_username` | path | string | Yes | Package username |
| `package_channel` | path | string | Yes | Package channel |
| `recipe_revision` | path | string | Yes | Conan Recipe Revision |
| `file_name` | path | enum: conanfile.py, conanmanifest.txt, conan_sources.tgz... | Yes | Package file name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 403 | Forbidden |
| 404 | Not Found |


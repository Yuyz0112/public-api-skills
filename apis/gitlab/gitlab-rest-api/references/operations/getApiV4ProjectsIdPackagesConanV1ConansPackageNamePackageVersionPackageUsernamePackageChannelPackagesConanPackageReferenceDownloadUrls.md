# GET /api/v4/projects/{id}/packages/conan/v1/conans/{package_name}/{package_version}/{package_username}/{package_channel}/packages/{conan_package_reference}/download_urls

**Resource:** [Packages](../resources/Packages.md)
**Package Download Urls**
**Operation ID:** `getApiV4ProjectsIdPackagesConanV1ConansPackageNamePackageVersionPackageUsernamePackageChannelPackagesConanPackageReferenceDownloadUrls`

This feature was introduced in GitLab 12.5

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `package_name` | path | string | Yes | Package name |
| `package_version` | query | string | Yes | Package version |
| `package_username` | path | string | Yes | Package username |
| `package_channel` | path | string | Yes | Package channel |
| `conan_package_reference` | path | string | Yes | Conan package ID |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 403 | Forbidden |
| 404 | Not Found |

**Success Response Schema:**

[APIEntitiesPackagesConanPackageManifest](../schemas/APIEntitiesPackagesConanPackageManifest/APIEntitiesPackagesConanPackageManifest.md)


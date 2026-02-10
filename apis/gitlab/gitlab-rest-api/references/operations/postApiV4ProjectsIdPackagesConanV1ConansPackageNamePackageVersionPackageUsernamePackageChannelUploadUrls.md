# POST /api/v4/projects/{id}/packages/conan/v1/conans/{package_name}/{package_version}/{package_username}/{package_channel}/upload_urls

**Resource:** [Packages](../resources/Packages.md)
**Recipe Upload Urls**
**Operation ID:** `postApiV4ProjectsIdPackagesConanV1ConansPackageNamePackageVersionPackageUsernamePackageChannelUploadUrls`

This feature was introduced in GitLab 12.4

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `package_name` | path | string | Yes | Package name |
| `package_username` | path | string | Yes | Package username |
| `package_channel` | path | string | Yes | Package channel |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 403 | Forbidden |
| 404 | Not Found |

**Success Response Schema:**

[APIEntitiesPackagesConanUploadUrls](../schemas/APIEntitiesPackagesConanUploadUrls/APIEntitiesPackagesConanUploadUrls.md)


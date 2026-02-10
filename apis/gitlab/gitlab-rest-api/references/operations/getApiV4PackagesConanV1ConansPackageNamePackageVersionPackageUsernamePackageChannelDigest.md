# GET /api/v4/packages/conan/v1/conans/{package_name}/{package_version}/{package_username}/{package_channel}/digest

**Resource:** [Packages](../resources/Packages.md)
**Recipe Digest**
**Operation ID:** `getApiV4PackagesConanV1ConansPackageNamePackageVersionPackageUsernamePackageChannelDigest`

This feature was introduced in GitLab 12.5

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `package_name` | path | string | Yes | Package name |
| `package_version` | query | string | Yes | Package version |
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

[APIEntitiesPackagesConanRecipeManifest](../schemas/APIEntitiesPackagesConanRecipeManifest/APIEntitiesPackagesConanRecipeManifest.md)


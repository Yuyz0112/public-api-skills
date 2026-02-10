# GET /api/v4/projects/{id}/packages/conan/v2/conans/{package_name}/{package_version}/{package_username}/{package_channel}/latest

**Resource:** [Packages](../resources/Packages.md)
**Get the latest recipe revision**
**Operation ID:** `getApiV4ProjectsIdPackagesConanV2ConansPackageNamePackageVersionPackageUsernamePackageChannelLatest`

This feature was introduced in GitLab 17.11

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `package_name` | path | string | Yes | Package name |
| `package_version` | query | string | Yes | Package version |
| `package_username` | path | string | Yes | Package username |
| `package_channel` | path | string | Yes | Package channel |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

**Success Response Schema:**

[APIEntitiesPackagesConanRevision](../schemas/APIEntitiesPackagesConanRevision/APIEntitiesPackagesConanRevision.md)


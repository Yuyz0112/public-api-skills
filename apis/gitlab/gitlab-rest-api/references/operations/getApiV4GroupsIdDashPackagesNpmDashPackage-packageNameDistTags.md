# GET /api/v4/groups/{id}/-/packages/npm/-/package/*package_name/dist-tags

**Resource:** [Packages](../resources/Packages.md)
**Get all tags for a given an NPM package**
**Operation ID:** `getApiV4GroupsIdDashPackagesNpmDashPackage*packageNameDistTags`

This feature was introduced in GitLab 12.7

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the group |
| `package_name` | query | string | Yes | Package name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

**Success Response Schema:**

[APIEntitiesNpmPackageTag](../schemas/APIEntitiesNpmPackageTag/APIEntitiesNpmPackageTag.md)


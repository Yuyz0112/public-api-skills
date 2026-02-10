# GET /api/v4/projects/{id}/packages/npm/*package_name

**Resource:** [Packages](../resources/Packages.md)
**NPM registry metadata endpoint**
**Operation ID:** `getApiV4ProjectsIdPackagesNpm*packageName`

This feature was introduced in GitLab 11.8

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `package_name` | query | string | Yes | Package name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Ok |
| 302 | Found (redirect) |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

**Success Response Schema:**

[APIEntitiesNpmPackage](../schemas/APIEntitiesNpmPackage/APIEntitiesNpmPackage.md)


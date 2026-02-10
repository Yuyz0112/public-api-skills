# GET /api/v4/packages/npm/*package_name

**Resource:** [Packages](../resources/Packages.md)
**NPM registry metadata endpoint**
**Operation ID:** `getApiV4PackagesNpm*packageName`

This feature was introduced in GitLab 11.8

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
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


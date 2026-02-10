# PUT /api/v4/projects/{id}/packages/npm/{package_name}

**Resource:** [Packages](../resources/Packages.md)
**Create or deprecate NPM package**
**Operation ID:** `putApiV4ProjectsIdPackagesNpmPackageName`

Create was introduced in GitLab 11.8 & deprecate suppport was added in 16.0

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `package_name` | path | string | Yes | Package name |

## Request Body

**Required:** Yes

**Content Types:** `multipart/form-data`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |


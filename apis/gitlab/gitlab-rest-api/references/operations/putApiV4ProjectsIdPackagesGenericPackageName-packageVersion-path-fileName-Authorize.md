# PUT /api/v4/projects/{id}/packages/generic/{package_name}/*package_version/(*path/){file_name}/authorize

**Resource:** [Packages](../resources/Packages.md)
**Workhorse authorize generic package file**
**Operation ID:** `putApiV4ProjectsIdPackagesGenericPackageName*packageVersion(*path){fileName}Authorize`

This feature was introduced in GitLab 13.5

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `package_name` | path | string | Yes | Package name |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |


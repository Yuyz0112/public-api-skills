# PUT /api/v4/projects/{id}/packages/generic/{package_name}/*package_version/(*path/){file_name}

**Resource:** [Packages](../resources/Packages.md)
**Upload package file**
**Operation ID:** `putApiV4ProjectsIdPackagesGenericPackageName*packageVersion(*path){fileName}`

This feature was introduced in GitLab 13.5

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
| 201 | Created |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |


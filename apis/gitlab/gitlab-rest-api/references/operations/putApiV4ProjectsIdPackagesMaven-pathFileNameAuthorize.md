# PUT /api/v4/projects/{id}/packages/maven/*path/{file_name}/authorize

**Resource:** [Packages](../resources/Packages.md)
**Workhorse authorize the maven package file upload**
**Operation ID:** `putApiV4ProjectsIdPackagesMaven*pathFileNameAuthorize`

This feature was introduced in GitLab 11.3

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `file_name` | path | string | Yes | Package file name |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |


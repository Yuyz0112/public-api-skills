# PUT /api/v4/projects/{id}/packages/debian/{file_name}/authorize

**Resource:** [Packages](../resources/Packages.md)
**Authorize Debian package upload**
**Operation ID:** `putApiV4ProjectsIdPackagesDebianFileNameAuthorize`

This feature was introduced in GitLab 13.5

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `file_name` | path | string | Yes | The filename |

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


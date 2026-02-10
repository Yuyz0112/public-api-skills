# GET /api/v4/projects/{id}/packages/maven/*path/{file_name}

**Resource:** [Packages](../resources/Packages.md)
**Download the maven package file at a project level**
**Operation ID:** `getApiV4ProjectsIdPackagesMaven*pathFileName`

This feature was introduced in GitLab 11.3

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `path` | query | string | Yes | Package path |
| `file_name` | path | string | Yes | Package file name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 302 | Found |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |


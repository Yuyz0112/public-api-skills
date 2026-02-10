# GET /api/v4/projects/{id}/packages/rubygems/quick/Marshal.4.8/{file_name}

**Resource:** [Packages](../resources/Packages.md)
**Download the gemspec file**
**Operation ID:** `getApiV4ProjectsIdPackagesRubygemsQuickMarshal48FileName`

This feature was introduced in GitLab 13.9

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `file_name` | path | string | Yes | Gemspec file name |

## Responses

| Status | Description |
|--------|-------------|
| 401 | Unauthorized |
| 404 | Not Found |


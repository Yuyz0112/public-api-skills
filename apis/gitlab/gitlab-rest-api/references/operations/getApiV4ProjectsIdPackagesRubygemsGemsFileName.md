# GET /api/v4/projects/{id}/packages/rubygems/gems/{file_name}

**Resource:** [Packages](../resources/Packages.md)
**Download the .gem package**
**Operation ID:** `getApiV4ProjectsIdPackagesRubygemsGemsFileName`

This feature was introduced in GitLab 13.9

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `file_name` | path | string | Yes | Package file name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |


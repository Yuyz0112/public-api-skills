# GET /api/v4/projects/{id}/packages/rubygems/{file_name}

**Resource:** [Packages](../resources/Packages.md)
**Download the spec index file**
**Operation ID:** `getApiV4ProjectsIdPackagesRubygemsFileName`

This feature was introduced in GitLab 13.9

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `file_name` | path | string | Yes | Spec file name |

## Responses

| Status | Description |
|--------|-------------|
| 401 | Unauthorized |
| 404 | Not Found |


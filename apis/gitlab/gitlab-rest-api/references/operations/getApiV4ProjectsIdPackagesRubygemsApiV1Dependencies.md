# GET /api/v4/projects/{id}/packages/rubygems/api/v1/dependencies

**Resource:** [Packages](../resources/Packages.md)
**Fetch a list of dependencies**
**Operation ID:** `getApiV4ProjectsIdPackagesRubygemsApiV1Dependencies`

This feature was introduced in GitLab 13.9

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `gems` | query | any | No | Comma delimited gem names |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |


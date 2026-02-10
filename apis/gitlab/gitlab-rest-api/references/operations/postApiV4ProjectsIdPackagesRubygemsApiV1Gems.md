# POST /api/v4/projects/{id}/packages/rubygems/api/v1/gems

**Resource:** [Packages](../resources/Packages.md)
**Upload a gem**
**Operation ID:** `postApiV4ProjectsIdPackagesRubygemsApiV1Gems`

This feature was introduced in GitLab 13.9

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Request Body

**Required:** Yes

**Content Types:** `multipart/form-data`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |


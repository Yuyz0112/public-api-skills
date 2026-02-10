# POST /api/v4/projects/{id}/packages/rubygems/api/v1/gems/authorize

**Resource:** [Packages](../resources/Packages.md)
**Authorize a gem upload from workhorse**
**Operation ID:** `postApiV4ProjectsIdPackagesRubygemsApiV1GemsAuthorize`

This feature was introduced in GitLab 13.9

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |


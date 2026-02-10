# GET /api/v4/projects/{id}/packages/conan/v1/conans/search

**Resource:** [Packages](../resources/Packages.md)
**Search for packages**
**Operation ID:** `getApiV4ProjectsIdPackagesConanV1ConansSearch`

This feature was introduced in GitLab 12.4

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `q` | query | string | Yes | Search query |
| `ignorecase` | query | boolean | No | Ignore case when searching (case-insensitive search) |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 404 | Not Found |


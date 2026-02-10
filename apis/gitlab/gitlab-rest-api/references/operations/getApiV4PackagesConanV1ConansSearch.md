# GET /api/v4/packages/conan/v1/conans/search

**Resource:** [Packages](../resources/Packages.md)
**Search for packages**
**Operation ID:** `getApiV4PackagesConanV1ConansSearch`

This feature was introduced in GitLab 12.4

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `q` | query | string | Yes | Search query |
| `ignorecase` | query | boolean | No | Ignore case when searching (case-insensitive search) |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 404 | Not Found |


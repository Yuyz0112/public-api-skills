# POST /api/v4/projects/{id}/packages/rpm/authorize

**Resource:** [Packages](../resources/Packages.md)
**Authorize package upload from workhorse**
**Operation ID:** `postApiV4ProjectsIdPackagesRpmAuthorize`

This feature was introduced in GitLab 15.7

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Responses

| Status | Description |
|--------|-------------|
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |


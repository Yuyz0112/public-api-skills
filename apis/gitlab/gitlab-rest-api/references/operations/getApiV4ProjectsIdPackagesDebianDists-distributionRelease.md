# GET /api/v4/projects/{id}/packages/debian/dists/*distribution/Release

**Resource:** [Packages](../resources/Packages.md)
**The unsigned Release file**
**Operation ID:** `getApiV4ProjectsIdPackagesDebianDists*distributionRelease`

This feature was introduced in GitLab 13.5

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `distribution` | query | string | Yes | The Debian Codename or Suite |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |


# POST /api/v4/projects/{id}/packages/rpm

**Resource:** [Packages](../resources/Packages.md)
**Upload a RPM package**
**Operation ID:** `postApiV4ProjectsIdPackagesRpm`

This feature was introduced in GitLab 15.7

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Responses

| Status | Description |
|--------|-------------|
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |


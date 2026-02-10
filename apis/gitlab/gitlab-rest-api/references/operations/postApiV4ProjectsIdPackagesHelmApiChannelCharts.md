# POST /api/v4/projects/{id}/packages/helm/api/{channel}/charts

**Resource:** [Packages](../resources/Packages.md)
**Upload a chart**
**Operation ID:** `postApiV4ProjectsIdPackagesHelmApiChannelCharts`

This feature was introduced in GitLab 14.0

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or full path of a project |
| `channel` | path | string | Yes | Helm channel |

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


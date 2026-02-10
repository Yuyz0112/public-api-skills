# GET /api/v4/projects/{id}/packages/helm/{channel}/charts/{file_name}.tgz

**Resource:** [Packages](../resources/Packages.md)
**Download a chart**
**Operation ID:** `getApiV4ProjectsIdPackagesHelmChannelChartsFileName}Tg`

This feature was introduced in GitLab 14.0

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or full path of a project |
| `channel` | path | string | Yes | Helm channel |
| `file_name` | path | string | Yes | Helm package file name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |


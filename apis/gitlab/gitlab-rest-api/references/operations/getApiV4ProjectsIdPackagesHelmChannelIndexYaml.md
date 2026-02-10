# GET /api/v4/projects/{id}/packages/helm/{channel}/index.yaml

**Resource:** [Packages](../resources/Packages.md)
**Download a chart index**
**Operation ID:** `getApiV4ProjectsIdPackagesHelmChannelIndexYaml`

This feature was introduced in GitLab 14.0

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or full path of a project |
| `channel` | path | string | Yes | Helm channel |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |


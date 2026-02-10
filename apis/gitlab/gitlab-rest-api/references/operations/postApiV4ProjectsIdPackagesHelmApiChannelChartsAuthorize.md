# POST /api/v4/projects/{id}/packages/helm/api/{channel}/charts/authorize

**Resource:** [Packages](../resources/Packages.md)
**Authorize a chart upload from workhorse**
**Operation ID:** `postApiV4ProjectsIdPackagesHelmApiChannelChartsAuthorize`

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
| 404 | Not Found |


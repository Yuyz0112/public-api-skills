# GET /api/v4/projects/{id}/packages/{package_id}/pipelines

**Resource:** [Packages](../resources/Packages.md)
**Get the pipelines for a single project package**
**Operation ID:** `getApiV4ProjectsIdPackagesPackageIdPipelines`

This feature was introduced in GitLab 16.1

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |
| `package_id` | path | integer | Yes | The ID of a package |
| `cursor` | query | string | No | Cursor for obtaining the next set of records |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

**Success Response Schema:**

[APIEntitiesPackagePipeline](../schemas/APIEntitiesPackagePipeline/APIEntitiesPackagePipeline.md)


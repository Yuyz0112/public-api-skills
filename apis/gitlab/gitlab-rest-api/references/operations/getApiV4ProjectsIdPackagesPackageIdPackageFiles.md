# GET /api/v4/projects/{id}/packages/{package_id}/package_files

**Resource:** [Packages](../resources/Packages.md)
**List package files**
**Operation ID:** `getApiV4ProjectsIdPackagesPackageIdPackageFiles`

Get a list of package files of a single package

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | ID or URL-encoded path of the project |
| `package_id` | path | integer | Yes | ID of a package |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |
| `order_by` | query | enum: id, created_at, file_name | No | Return package files ordered by `id`, `created_at` or `file_name` |
| `sort` | query | enum: asc, desc | No | Return package files sorted in `asc` or `desc` order. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesPackageFile](../schemas/APIEntitiesPackageFile/APIEntitiesPackageFile.md)


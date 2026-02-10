# GET /api/v4/projects/{id}/packages

**Resource:** [Packages](../resources/Packages.md)
**Get a list of project packages**
**Operation ID:** `getApiV4ProjectsIdPackages`

This feature was introduced in GitLab 11.8

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |
| `order_by` | query | enum: created_at, name, version... | No | Return packages ordered by `created_at`, `name`, `version` or `type` fields. |
| `sort` | query | enum: asc, desc | No | Return packages sorted in `asc` or `desc` order. |
| `package_type` | query | enum: maven, npm, conan... | No | Return packages of a certain type |
| `package_name` | query | string | No | Return packages with this name |
| `package_version` | query | string | No | Return packages with this version |
| `include_versionless` | query | boolean | No | Returns packages without a version |
| `status` | query | enum: default, hidden, processing... | No | Return packages with specified status |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 403 | Forbidden |
| 404 | Project Not Found |

**Success Response Schema:**

[APIEntitiesPackage](../schemas/APIEntitiesPackage/APIEntitiesPackage.md)


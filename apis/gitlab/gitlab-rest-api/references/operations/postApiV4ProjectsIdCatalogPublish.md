# POST /api/v4/projects/{id}/catalog/publish

**Resource:** [CI catalog](../resources/CI-catalog.md)
**Publish a new component project release as version to the CI/CD catalog**
**Operation ID:** `postApiV4ProjectsIdCatalogPublish`

Publishes a release of a catalog resource as version to the CI/CD catalog.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |
| 422 | Unprocessable entity |

**Success Response Schema:**

[APIEntitiesCiCatalogResourcesVersion](../schemas/APIEntitiesCiCatalogResourcesVersion/APIEntitiesCiCatalogResourcesVersion.md)


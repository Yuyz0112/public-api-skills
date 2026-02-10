# GET /api/v4/geo_sites/{id}/status

**Resource:** [Geo](../resources/Geo.md)
**Get metrics for a single Geo site**
**Operation ID:** `getApiV4GeoSitesIdStatus`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes |  |
| `refresh` | query | boolean | No | Attempt to fetch the latest status from the Geo site directly, ignoring the cache |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | 400 Bad request |
| 401 | 401 Unauthorized |
| 403 | 403 Forbidden |
| 404 | 404 GeoSite Not Found |

**Success Response Schema:**

[APIEntitiesGeoSiteStatus](../schemas/APIEntitiesGeoSiteStatus/APIEntitiesGeoSiteStatus.md)


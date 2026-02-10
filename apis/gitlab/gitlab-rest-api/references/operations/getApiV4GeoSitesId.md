# GET /api/v4/geo_sites/{id}

**Resource:** [Geo](../resources/Geo.md)
**Get a single GeoSite**
**Operation ID:** `getApiV4GeoSitesId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | 400 Bad request |
| 401 | 401 Unauthorized |
| 403 | 403 Forbidden |
| 404 | 404 GeoSite Not Found |

**Success Response Schema:**

[APIEntitiesGeoSite](../schemas/APIEntitiesGeoSite/APIEntitiesGeoSite.md)


# POST /api/v4/geo_sites/{id}/repair

**Resource:** [Geo](../resources/Geo.md)
**Repair authentication of the Geo site**
**Operation ID:** `postApiV4GeoSitesIdRepair`

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

[APIEntitiesGeoSiteStatus](../schemas/APIEntitiesGeoSiteStatus/APIEntitiesGeoSiteStatus.md)


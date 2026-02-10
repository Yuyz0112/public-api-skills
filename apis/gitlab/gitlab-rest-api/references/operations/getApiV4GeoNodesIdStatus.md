# GET /api/v4/geo_nodes/{id}/status

**Resource:** [Geo](../resources/Geo.md)
**Get metrics for a single Geo node**
**Operation ID:** `getApiV4GeoNodesIdStatus`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes |  |
| `refresh` | query | boolean | No | Attempt to fetch the latest status from the Geo node directly, ignoring the cache |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | 400 Bad request |
| 401 | 401 Unauthorized |
| 403 | 403 Forbidden |
| 404 | 404 GeoNode Not Found |

**Success Response Schema:**

[APIEntitiesGeoNodeStatus](../schemas/APIEntitiesGeoNodeStatus/APIEntitiesGeoNodeStatus.md)


# GET /api/v4/geo_nodes/{id}

**Resource:** [Geo](../resources/Geo.md)
**Get a single GeoNode**
**Operation ID:** `getApiV4GeoNodesId`

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
| 404 | 404 GeoNode Not Found |

**Success Response Schema:**

[APIEntitiesGeoNode](../schemas/APIEntitiesGeoNode/APIEntitiesGeoNode.md)


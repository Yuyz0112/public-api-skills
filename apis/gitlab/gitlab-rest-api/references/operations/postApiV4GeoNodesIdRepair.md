# POST /api/v4/geo_nodes/{id}/repair

**Resource:** [Geo](../resources/Geo.md)
**Repair authentication of the Geo node**
**Operation ID:** `postApiV4GeoNodesIdRepair`

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

[APIEntitiesGeoNodeStatus](../schemas/APIEntitiesGeoNodeStatus/APIEntitiesGeoNodeStatus.md)


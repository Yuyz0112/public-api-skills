# GET /api/v4/geo_nodes/status

**Resource:** [Geo](../resources/Geo.md)
**Get status for all Geo nodes**
**Operation ID:** `getApiV4GeoNodesStatus`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | 400 Bad request |
| 401 | 401 Unauthorized |
| 403 | 403 Forbidden |

**Success Response Schema:**

[APIEntitiesGeoNodeStatus](../schemas/APIEntitiesGeoNodeStatus/APIEntitiesGeoNodeStatus.md)


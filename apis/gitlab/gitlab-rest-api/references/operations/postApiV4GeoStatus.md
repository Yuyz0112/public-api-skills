# POST /api/v4/geo/status

**Resource:** [Geo](../resources/Geo.md)
**Posts the current node status to the primary site**
**Operation ID:** `postApiV4GeoStatus`

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | 400 Bad Request |
| 401 | 401 Unauthorized |

**Success Response Schema:**

[APIEntitiesGeoNodeStatus](../schemas/APIEntitiesGeoNodeStatus/APIEntitiesGeoNodeStatus.md)


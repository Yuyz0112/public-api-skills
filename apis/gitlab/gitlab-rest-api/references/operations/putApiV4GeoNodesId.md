# PUT /api/v4/geo_nodes/{id}

**Resource:** [Geo](../resources/Geo.md)
**Updates an existing Geo node**
**Operation ID:** `putApiV4GeoNodesId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes |  |

## Request Body

**Content Types:** `application/json`

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


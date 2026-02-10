# DELETE /api/v4/geo_sites/{id}

**Resource:** [Geo](../resources/Geo.md)
**Remove the Geo site**
**Operation ID:** `deleteApiV4GeoSitesId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 400 | 400 Bad request |
| 401 | 401 Unauthorized |
| 403 | 403 Forbidden |
| 404 | 404 GeoSite Not Found |


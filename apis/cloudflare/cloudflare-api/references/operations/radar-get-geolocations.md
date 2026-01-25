# GET /radar/geolocations

**Resource:** [Radar Geolocations](../resources/Radar-Geolocations.md)
**List Geolocations**
**Operation ID:** `radar-get-geolocations`

Retrieves a list of geolocations.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `limit` | query | integer | No | Limits the number of objects returned in the response. |
| `offset` | query | integer | No | Skips the specified number of objects before fetching the results. |
| `geoId` | query | string | No | Filters results by geolocation. Specify a comma-separated list of GeoNames IDs. |
| `location` | query | string | No | Filters results by location. Specify a comma-separated list of alpha-2 location codes. |
| `format` | query | enum: JSON, CSV | No | Format in which results will be returned. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| 400 | Bad request. |

## Security

- **api_email**
- **api_key**
- **api_token**

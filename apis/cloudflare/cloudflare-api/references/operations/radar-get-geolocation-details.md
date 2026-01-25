# GET /radar/geolocations/{geo_id}

**Resource:** [Radar Geolocations](../resources/Radar-Geolocations.md)
**Get Geolocation details**
**Operation ID:** `radar-get-geolocation-details`

Retrieves the requested Geolocation information.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `geo_id` | path | string | Yes | Geolocation ID. Refer to [GeoNames](https://download.geonames.org/export/dump/readme.txt) |
| `format` | query | enum: JSON, CSV | No | Format in which results will be returned. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| 404 | Not found. |

## Security

- **api_email**
- **api_key**
- **api_token**

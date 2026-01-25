# GET /radar/entities/locations/{location}

**Resource:** [Radar Locations](../resources/Radar-Locations.md)
**Get location details**
**Operation ID:** `radar-get-entities-location-by-alpha2`

Retrieves the requested location information. (A confidence level below `5` indicates a low level of confidence in the traffic data - normally this happens because Cloudflare has a small amount of traffic from/to this location).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `location` | path | string | Yes | Location alpha-2 code. |
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

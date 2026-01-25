# GET /radar/entities/locations

**Resource:** [Radar Locations](../resources/Radar-Locations.md)
**List locations**
**Operation ID:** `radar-get-entities-locations`

Retrieves a list of locations.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `limit` | query | integer | No | Limits the number of objects returned in the response. |
| `offset` | query | integer | No | Skips the specified number of objects before fetching the results. |
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

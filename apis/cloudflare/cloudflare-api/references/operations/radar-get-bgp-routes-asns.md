# GET /radar/bgp/routes/ases

**Resource:** [Radar BGP](../resources/Radar-BGP.md)
**List ASes from global routing tables**
**Operation ID:** `radar-get-bgp-routes-asns`

Retrieves all ASes in the current global routing tables with routing statistics.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `location` | query | string | No | Filters results by location. Specify an alpha-2 location code. |
| `limit` | query | integer | No | Limits the number of objects returned in the response. |
| `sortBy` | query | enum: cone, pfxs, ipv4... | No | Sorts results by the specified field. |
| `sortOrder` | query | enum: ASC, DESC | No | Sort order. |
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

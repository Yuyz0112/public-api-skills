# GET /radar/bgp/top/ases/prefixes

**Resource:** [Radar BGP](../resources/Radar-BGP.md)
**Get top ASes by prefix count**
**Operation ID:** `radar-get-bgp-top-asns-by-prefixes`

Retrieves the full list of autonomous systems on the global routing table ordered by announced prefixes count. The data comes from public BGP MRT data archives and updates every 2 hours.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `country` | query | string | No | Alpha-2 country code. |
| `limit` | query | integer | No | Maximum number of ASes to return. |
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

# GET /radar/bgp/routes/stats

**Resource:** [Radar BGP](../resources/Radar-BGP.md)
**Get BGP routing table stats **
**Operation ID:** `radar-get-bgp-routes-stats`

Retrieves the BGP routing table stats.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `asn` | query | integer | No | Filters results by Autonomous System. Specify a single Autonomous System Number (ASN) as integer. |
| `location` | query | string | No | Filters results by location. Specify an alpha-2 location code. |
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

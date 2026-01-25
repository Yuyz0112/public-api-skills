# GET /radar/bgp/routes/realtime

**Resource:** [Radar BGP](../resources/Radar-BGP.md)
**Get real-time BGP routes for a prefix**
**Operation ID:** `radar-get-bgp-routes-realtime`

Retrieves real-time BGP routes for a prefix, using public real-time data collectors (RouteViews and RIPE RIS).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `prefix` | query | string | No |  |
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

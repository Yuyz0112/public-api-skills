# GET /radar/entities/asns/ip

**Resource:** [Radar Autonomous Systems](../resources/Radar-Autonomous-Systems.md)
**Get AS details by IP address**
**Operation ID:** `radar-get-entities-asn-by-ip`

Retrieves the requested autonomous system information based on IP address. Population estimates come from APNIC (refer to https://labs.apnic.net/?p=526).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `ip` | query | string (ip) | Yes | IP address. |
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

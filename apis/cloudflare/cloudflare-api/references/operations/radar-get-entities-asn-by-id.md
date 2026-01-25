# GET /radar/entities/asns/{asn}

**Resource:** [Radar Autonomous Systems](../resources/Radar-Autonomous-Systems.md)
**Get AS details by ASN**
**Operation ID:** `radar-get-entities-asn-by-id`

Retrieves the requested autonomous system information. (A confidence level below `5` indicates a low level of confidence in the traffic data - normally this happens because Cloudflare has a small amount of traffic from/to this AS). Population estimates come from APNIC (refer to https://labs.apnic.net/?p=526).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `asn` | path | integer | Yes | Single Autonomous System Number (ASN) as integer. |
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

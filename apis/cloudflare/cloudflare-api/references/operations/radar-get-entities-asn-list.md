# GET /radar/entities/asns

**Resource:** [Radar Autonomous Systems](../resources/Radar-Autonomous-Systems.md)
**List autonomous systems**
**Operation ID:** `radar-get-entities-asn-list`

Retrieves a list of autonomous systems.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `limit` | query | integer | No | Limits the number of objects returned in the response. |
| `offset` | query | integer | No | Skips the specified number of objects before fetching the results. |
| `asn` | query | string | No | Filters results by Autonomous System. Specify one or more Autonomous System Numbers (ASNs) as a comma-separated list. |
| `location` | query | string | No | Filters results by location. Specify an alpha-2 location code. |
| `orderBy` | query | enum: ASN, POPULATION | No | Specifies the metric to order the ASNs by. |
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

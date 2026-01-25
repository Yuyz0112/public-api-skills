# GET /radar/entities/asns/{asn}/as_set

**Resource:** [Radar Autonomous Systems](../resources/Radar-Autonomous-Systems.md)
**Get IRR AS-SETs that an AS is a member of**
**Operation ID:** `radar-get-asns-as-set`

Retrieves Internet Routing Registry AS-SETs that an AS is a member of.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `asn` | path | integer | Yes | Retrieves all AS-SETs that the given AS is a member of. |
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

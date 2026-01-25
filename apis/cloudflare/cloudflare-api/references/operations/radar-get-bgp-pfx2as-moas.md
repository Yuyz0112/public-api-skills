# GET /radar/bgp/routes/moas

**Resource:** [Radar BGP](../resources/Radar-BGP.md)
**Get Multi-Origin AS (MOAS) prefixes**
**Operation ID:** `radar-get-bgp-pfx2as-moas`

Retrieves all Multi-Origin AS (MOAS) prefixes in the global routing tables.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `origin` | query | integer | No | Lookup MOASes originated by the given ASN. |
| `prefix` | query | string | No |  |
| `invalid_only` | query | boolean | No | Lookup only RPKI invalid MOASes. |
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

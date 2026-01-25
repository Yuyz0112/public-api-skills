# GET /radar/bgp/routes/pfx2as

**Resource:** [Radar BGP](../resources/Radar-BGP.md)
**Get prefix-to-ASN mapping**
**Operation ID:** `radar-get-bgp-pfx2as`

Retrieves the prefix-to-ASN mapping from global routing tables.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `prefix` | query | string | No |  |
| `origin` | query | integer | No | Lookup prefixes originated by the given ASN. |
| `rpkiStatus` | query | enum: VALID, INVALID, UNKNOWN | No | Return only results with matching rpki status: valid, invalid or unknown. |
| `longestPrefixMatch` | query | boolean | No | Return only results with the longest prefix match for the given prefix. For example, specify a /32 prefix to lookup the origin ASN for an IPv4 address. |
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

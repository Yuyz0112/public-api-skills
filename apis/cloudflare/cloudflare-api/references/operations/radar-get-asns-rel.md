# GET /radar/entities/asns/{asn}/rel

**Resource:** [Radar Autonomous Systems](../resources/Radar-Autonomous-Systems.md)
**Get AS-level relationships by ASN**
**Operation ID:** `radar-get-asns-rel`

Retrieves AS-level relationship for given networks.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `asn` | path | integer | Yes | Retrieves all ASNs with provider-customer or peering relationships with the given ASN. |
| `asn2` | query | integer | No | Retrieves the AS relationship of ASN2 with respect to the given ASN. |
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

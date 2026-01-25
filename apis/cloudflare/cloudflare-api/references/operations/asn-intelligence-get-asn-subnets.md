# GET /accounts/{account_id}/intel/asn/{asn}/subnets

**Resource:** [ASN Intelligence](../resources/ASN-Intelligence.md)
**Get ASN Subnets**
**Operation ID:** `asn-intelligence-get-asn-subnets`

Get ASN Subnets.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `asn` | path | intel_asn | Yes |  |
| `account_id` | path | intel_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get ASN Subnets response. |
| 4XX | Get ASN Subnets response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**

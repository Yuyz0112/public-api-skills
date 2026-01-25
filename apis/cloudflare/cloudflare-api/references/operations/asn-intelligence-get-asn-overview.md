# GET /accounts/{account_id}/intel/asn/{asn}

**Resource:** [ASN Intelligence](../resources/ASN-Intelligence.md)
**Get ASN Overview.**
**Operation ID:** `asn-intelligence-get-asn-overview`

Gets an overview of the Autonomous System Number (ASN) and a list of subnets for it.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `asn` | path | intel_asn | Yes |  |
| `account_id` | path | intel_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get ASN Overview response. |
| 4XX | Get ASN Overview response failure. |

**Success Response Schema:**

[intel_asn_components-schemas-response](../schemas/intel/intel-asn-components-schemas-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**

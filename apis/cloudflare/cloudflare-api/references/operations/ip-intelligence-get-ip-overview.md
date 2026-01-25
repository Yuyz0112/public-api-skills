# GET /accounts/{account_id}/intel/ip

**Resource:** [IP Intelligence](../resources/IP-Intelligence.md)
**Get IP Overview**
**Operation ID:** `ip-intelligence-get-ip-overview`

Gets the geolocation, ASN, infrastructure type of the ASN, and any security threat categories of an IP address. **Must provide ip query parameters.** For example, `/intel/ip?ipv4=1.1.1.1` or `/intel/ip?ipv6=2001:db8::1`.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | intel_identifier | Yes |  |
| `ipv4` | query | string | No |  |
| `ipv6` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get IP Overview response. |
| 4XX | Get IP Overview response failure. |

**Success Response Schema:**

[intel_schemas-response](../schemas/intel/intel-schemas-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**

# GET /accounts/{account_id}/addressing/prefixes/{prefix_id}/bgp/prefixes/{bgp_prefix_id}

**Resource:** [IP Address Management BGP Prefixes](../resources/IP-Address-Management-BGP-Prefixes.md)
**Fetch BGP Prefix**
**Operation ID:** `ip-address-management-prefixes-fetch-bgp-prefix`

Retrieve a single BGP Prefix according to its identifier

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | addressing_account_identifier | Yes |  |
| `prefix_id` | path | addressing_prefix_identifier | Yes |  |
| `bgp_prefix_id` | path | addressing_bgp_prefix_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Fetch BGP Prefix response |
| 4XX | Fetch BGP Prefix response failure |

**Success Response Schema:**

[addressing_single_response_bgp](../schemas/addressing/addressing-single-response-bgp.md)

## Security

- **api_email**
- **api_key**

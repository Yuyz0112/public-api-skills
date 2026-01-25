# GET /accounts/{account_id}/addressing/prefixes/{prefix_id}/bgp/prefixes

**Resource:** [IP Address Management BGP Prefixes](../resources/IP-Address-Management-BGP-Prefixes.md)
**List BGP Prefixes**
**Operation ID:** `ip-address-management-prefixes-list-bgp-prefixes`

List all BGP Prefixes within the specified IP Prefix. BGP Prefixes are used to control which specific subnets are advertised to the Internet. It is possible to advertise subnets more specific than an IP Prefix by creating more specific BGP Prefixes.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | addressing_account_identifier | Yes |  |
| `prefix_id` | path | addressing_prefix_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List BGP Prefixes response |
| 4XX | List BGP Prefixes response failure |

**Success Response Schema:**

[addressing_response_collection_bgp](../schemas/addressing/addressing-response-collection-bgp.md)

## Security

- **api_email**
- **api_key**

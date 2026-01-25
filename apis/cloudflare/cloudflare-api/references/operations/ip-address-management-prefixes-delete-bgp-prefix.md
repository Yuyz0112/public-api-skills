# DELETE /accounts/{account_id}/addressing/prefixes/{prefix_id}/bgp/prefixes/{bgp_prefix_id}

**Resource:** [IP Address Management BGP Prefixes](../resources/IP-Address-Management-BGP-Prefixes.md)
**Delete BGP Prefix**
**Operation ID:** `ip-address-management-prefixes-delete-bgp-prefix`

Delete a BGP Prefix associated with the specified IP Prefix. A BGP Prefix must be withdrawn before it can be deleted.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | addressing_account_identifier | Yes |  |
| `prefix_id` | path | addressing_prefix_identifier | Yes |  |
| `bgp_prefix_id` | path | addressing_bgp_prefix_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete BGP Prefix response |
| 4XX | Delete BGP Prefix response failure |

**Success Response Schema:**

[addressing_api-response-common](../schemas/addressing/addressing-api-response-common.md)

## Security

- **api_email**
- **api_key**

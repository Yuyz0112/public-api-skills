# PATCH /accounts/{account_id}/addressing/prefixes/{prefix_id}/bgp/prefixes/{bgp_prefix_id}

**Resource:** [IP Address Management BGP Prefixes](../resources/IP-Address-Management-BGP-Prefixes.md)
**Update BGP Prefix**
**Operation ID:** `ip-address-management-prefixes-update-bgp-prefix`

Update the properties of a BGP Prefix, such as the on demand advertisement status (advertised or withdrawn).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | addressing_account_identifier | Yes |  |
| `prefix_id` | path | addressing_prefix_identifier | Yes |  |
| `bgp_prefix_id` | path | addressing_bgp_prefix_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [addressing_bgp_prefix_update_advertisement](../schemas/addressing/addressing-bgp-prefix-update-advertisement.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update BGP Prefix response |
| 4XX | Update BGP Prefix response failure |

**Success Response Schema:**

[addressing_single_response_bgp](../schemas/addressing/addressing-single-response-bgp.md)

## Security

- **api_email**
- **api_key**

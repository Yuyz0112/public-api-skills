# POST /accounts/{account_id}/addressing/prefixes/{prefix_id}/bgp/prefixes

**Resource:** [IP Address Management BGP Prefixes](../resources/IP-Address-Management-BGP-Prefixes.md)
**Create BGP Prefix**
**Operation ID:** `ip-address-management-prefixes-create-bgp-prefix`

Create a BGP prefix, controlling the BGP advertisement status of a specific subnet. When created, BGP prefixes are initially withdrawn, and can be advertised with the Update BGP Prefix API.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | addressing_account_identifier | Yes |  |
| `prefix_id` | path | addressing_prefix_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [addressing_bgp_prefix_create](../schemas/addressing/addressing-bgp-prefix-create.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create BGP Prefix response |
| 4XX | Create BGP Prefix response failure |

**Success Response Schema:**

[addressing_single_response_bgp](../schemas/addressing/addressing-single-response-bgp.md)

## Security

- **api_email**
- **api_key**

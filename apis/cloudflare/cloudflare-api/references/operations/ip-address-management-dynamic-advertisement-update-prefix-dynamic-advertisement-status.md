# PATCH /accounts/{account_id}/addressing/prefixes/{prefix_id}/bgp/status

**Resource:** [IP Address Management Dynamic Advertisement](../resources/IP-Address-Management-Dynamic-Advertisement.md)
**Update Prefix Dynamic Advertisement Status**
**Operation ID:** `ip-address-management-dynamic-advertisement-update-prefix-dynamic-advertisement-status`
⚠️ **Deprecated**

Advertise or withdraw the BGP route for a prefix.

**Deprecated:** Prefer the BGP Prefixes endpoints, which additionally allow for advertising and withdrawing 
subnets of an IP prefix.


## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `prefix_id` | path | addressing_prefix_identifier | Yes |  |
| `account_id` | path | addressing_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update Prefix Dynamic Advertisement Status response |
| 4XX | Update Prefix Dynamic Advertisement Status response failure |

**Success Response Schema:**

[addressing_advertised_response](../schemas/addressing/addressing-advertised-response.md)

## Security

- **api_email**
- **api_key**

# DELETE /accounts/{account_id}/teamnet/virtual_networks/{virtual_network_id}

**Resource:** [Tunnel Virtual Network](../resources/Tunnel-Virtual-Network.md)
**Delete a virtual network**
**Operation ID:** `tunnel-virtual-network-delete`

Deletes an existing virtual network.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `virtual_network_id` | path | tunnel_virtual_network_id | Yes |  |
| `account_id` | path | tunnel_account_id | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete a virtual network response |
| 4XX | Delete a virtual network response failure |

**Success Response Schema:**

[tunnel_vnet_response_single](../schemas/tunnel/tunnel-vnet-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
- **user_service_key**

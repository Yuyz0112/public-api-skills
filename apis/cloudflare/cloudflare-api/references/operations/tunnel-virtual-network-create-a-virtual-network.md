# POST /accounts/{account_id}/teamnet/virtual_networks

**Resource:** [Tunnel Virtual Network](../resources/Tunnel-Virtual-Network.md)
**Create a virtual network**
**Operation ID:** `tunnel-virtual-network-create-a-virtual-network`

Adds a new virtual network to an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | tunnel_account_id | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create a virtual network response |
| 4XX | Create a virtual network response failure |

**Success Response Schema:**

[tunnel_vnet_response_single](../schemas/tunnel/tunnel-vnet-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
- **user_service_key**

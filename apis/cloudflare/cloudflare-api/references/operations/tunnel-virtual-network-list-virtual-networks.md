# GET /accounts/{account_id}/teamnet/virtual_networks

**Resource:** [Tunnel Virtual Network](../resources/Tunnel-Virtual-Network.md)
**List virtual networks**
**Operation ID:** `tunnel-virtual-network-list-virtual-networks`

Lists and filters virtual networks in an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | tunnel_account_id | Yes |  |
| `id` | query | tunnel_virtual_network_id | No |  |
| `name` | query | tunnel_virtual_network_name | No |  |
| `is_default` | query | boolean | No |  |
| `is_default_network` | query | boolean | No |  |
| `is_deleted` | query | boolean | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List virtual networks response |
| 4XX | List virtual networks response failure |

**Success Response Schema:**

[tunnel_vnet_response_collection](../schemas/tunnel/tunnel-vnet-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
- **user_service_key**

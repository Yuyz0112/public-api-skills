# DELETE /accounts/{account_id}/teamnet/routes/{route_id}

**Resource:** [Tunnel Routing](../resources/Tunnel-Routing.md)
**Delete a tunnel route**
**Operation ID:** `tunnel-route-delete-a-tunnel-route`

Deletes a private network route from an account.


## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `route_id` | path | tunnel_route_id | Yes |  |
| `account_id` | path | tunnel_account_id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete a tunnel route response |
| 4XX | Delete a tunnel route response failure |

**Success Response Schema:**

[tunnel_route_response_single](../schemas/tunnel/tunnel-route-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
- **user_service_key**

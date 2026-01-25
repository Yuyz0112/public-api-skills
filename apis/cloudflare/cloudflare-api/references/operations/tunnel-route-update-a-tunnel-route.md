# PATCH /accounts/{account_id}/teamnet/routes/{route_id}

**Resource:** [Tunnel Routing](../resources/Tunnel-Routing.md)
**Update a tunnel route**
**Operation ID:** `tunnel-route-update-a-tunnel-route`

Updates an existing private network route in an account. The fields that are meant to be updated should be provided in the body of the request.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `route_id` | path | tunnel_route_id | Yes |  |
| `account_id` | path | tunnel_account_id | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update a tunnel route response |
| 4XX | Update a tunnel route response failure |

**Success Response Schema:**

[tunnel_route_response_single](../schemas/tunnel/tunnel-route-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
- **user_service_key**

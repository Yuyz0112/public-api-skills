# GET /accounts/{account_id}/zerotrust/routes/hostname/{hostname_route_id}

**Resource:** [Zero Trust Hostname Route](../resources/Zero-Trust-Hostname-Route.md)
**Get hostname route**
**Operation ID:** `zero-trust-networks-route-hostname-get`

Get a hostname route.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | tunnel_account_id | Yes |  |
| `hostname_route_id` | path | tunnel_hostname_route_id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get hostname route response |
| 4XX | Get hostname route response failure |

**Success Response Schema:**

[tunnel_hostname_route_response_single](../schemas/tunnel/tunnel-hostname-route-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
- **user_service_key**

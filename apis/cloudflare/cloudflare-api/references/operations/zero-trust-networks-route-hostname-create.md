# POST /accounts/{account_id}/zerotrust/routes/hostname

**Resource:** [Zero Trust Hostname Route](../resources/Zero-Trust-Hostname-Route.md)
**Create hostname route**
**Operation ID:** `zero-trust-networks-route-hostname-create`

Create a hostname route.

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
| 200 | Create hostname route response |
| 4XX | Create hostname route response failure |

**Success Response Schema:**

[tunnel_hostname_route_response_single](../schemas/tunnel/tunnel-hostname-route-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
- **user_service_key**

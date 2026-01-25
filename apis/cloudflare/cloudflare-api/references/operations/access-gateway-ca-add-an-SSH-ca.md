# POST /accounts/{account_id}/access/gateway_ca

**Resource:** [Gateway CA](../resources/Gateway-CA.md)
**Add a new SSH Certificate Authority (CA)**
**Operation ID:** `access-gateway-ca-add-an-SSH-ca`

Adds a new SSH Certificate Authority (CA).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | access_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 201 | Add a new SSH Certificate Authority (CA) response |
| 4XX | Add a new SSH Certificate Authority (CA) response failure |

**Success Response Schema:**

[access_gateway_ca_components-schemas-single_response](../schemas/access/access-gateway-ca-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

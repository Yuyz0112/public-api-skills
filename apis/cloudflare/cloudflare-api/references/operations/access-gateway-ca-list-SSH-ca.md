# GET /accounts/{account_id}/access/gateway_ca

**Resource:** [Gateway CA](../resources/Gateway-CA.md)
**List SSH Certificate Authorities (CA)**
**Operation ID:** `access-gateway-ca-list-SSH-ca`

Lists SSH Certificate Authorities (CA).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | access_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List SSH Certificate Authorities (CA) response |
| 4XX | List SSH Certificate Authorities (CA) response failure |

**Success Response Schema:**

[access_gateway_ca_components-schemas-response_collection](../schemas/access/access-gateway-ca-components-schemas-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**

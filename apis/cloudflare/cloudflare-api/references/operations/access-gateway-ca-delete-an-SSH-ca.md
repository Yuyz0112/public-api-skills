# DELETE /accounts/{account_id}/access/gateway_ca/{certificate_id}

**Resource:** [Gateway CA](../resources/Gateway-CA.md)
**Delete an SSH Certificate Authority (CA)**
**Operation ID:** `access-gateway-ca-delete-an-SSH-ca`

Deletes an SSH Certificate Authority.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `certificate_id` | path | access_uuid | Yes |  |
| `account_id` | path | access_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete an SSH Certificate Authority (CA) response |
| 4XX | Delete an SSH Certificate Authority (CA) response failure |

**Success Response Schema:**

[access_id_response](../schemas/access/access-id-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

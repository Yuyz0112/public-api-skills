# GET /accounts/{account_id}/addressing/prefixes/{prefix_id}/bindings/{binding_id}

**Resource:** [IP Address Management Service Bindings](../resources/IP-Address-Management-Service-Bindings.md)
**Get Service Binding**
**Operation ID:** `ip-address-management-service-bindings-get-service-binding`

Fetch a single Service Binding

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | addressing_account_identifier | Yes |  |
| `prefix_id` | path | addressing_prefix_identifier | Yes |  |
| `binding_id` | path | addressing_service_binding_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The Service Binding with the requested ID |
| 4XX | Get Service Binding response failure |

## Security

- **api_email**
- **api_key**

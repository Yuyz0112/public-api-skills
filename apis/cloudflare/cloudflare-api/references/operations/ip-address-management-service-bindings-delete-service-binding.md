# DELETE /accounts/{account_id}/addressing/prefixes/{prefix_id}/bindings/{binding_id}

**Resource:** [IP Address Management Service Bindings](../resources/IP-Address-Management-Service-Bindings.md)
**Delete Service Binding**
**Operation ID:** `ip-address-management-service-bindings-delete-service-binding`

Delete a Service Binding

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | addressing_account_identifier | Yes |  |
| `prefix_id` | path | addressing_prefix_identifier | Yes |  |
| `binding_id` | path | addressing_service_binding_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Service Binding deleted |
| 4XX | Delete Service Binding response failure |

**Success Response Schema:**

[addressing_api-response-common](../schemas/addressing/addressing-api-response-common.md)

## Security

- **api_email**
- **api_key**

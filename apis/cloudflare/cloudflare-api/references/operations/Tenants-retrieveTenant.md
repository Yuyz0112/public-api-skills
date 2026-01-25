# GET /tenants/{tenant_id}

**Resource:** [Tenants](../resources/Tenants.md)
**Get tenant**
**Operation ID:** `Tenants_retrieveTenant`

Retrieves a Tenant by Tenant ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `tenant_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| 4XX | An unexpected error response. |

## Security

- **api_email**
- **api_key**

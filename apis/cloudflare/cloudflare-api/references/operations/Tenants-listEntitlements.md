# GET /tenants/{tenant_id}/entitlements

**Resource:** [Tenants](../resources/Tenants.md)
**List tenant entitlements**
**Operation ID:** `Tenants_listEntitlements`

List of innate entitlements available for the Tenant.

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

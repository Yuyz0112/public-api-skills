# GET /tenants/{tenant_id}/accounts

**Resource:** [Tenants](../resources/Tenants.md)
**List tenant accounts**
**Operation ID:** `Tenants_listAccounts`

List of accounts for the Tenant.

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

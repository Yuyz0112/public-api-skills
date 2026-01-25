# GET /tenants/{tenant_id}/account_types

**Resource:** [Tenants](../resources/Tenants.md)
**Get tenant account types**
**Operation ID:** `Tenants_validAccountTypes`

List of account types available for the Tenant to provision accounts.

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

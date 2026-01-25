# GET /tenants/{tenant_id}/memberships

**Resource:** [Tenants](../resources/Tenants.md)
**List tenant memberships**
**Operation ID:** `Tenants_listMemberships`

List of active members (Cloudflare users) for the Tenant.

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

# POST /accounts/{account_id}/devices/registrations/revoke

**Resource:** [Registrations](../resources/Registrations.md)
**Revoke registrations**
**Operation ID:** `revoke-registrations`

Revokes a list of WARP registrations.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `id` | query | string[] | Yes | A list of registration IDs to revoke. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Revoke registrations response. |

## Security

- **api_token**

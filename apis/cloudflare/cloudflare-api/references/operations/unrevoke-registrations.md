# POST /accounts/{account_id}/devices/registrations/unrevoke

**Resource:** [Registrations](../resources/Registrations.md)
**Unrevoke registrations**
**Operation ID:** `unrevoke-registrations`

Unrevokes a list of WARP registrations.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `id` | query | string[] | Yes | A list of registration IDs to unrevoke. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Unrevoke registrations response. |

## Security

- **api_token**

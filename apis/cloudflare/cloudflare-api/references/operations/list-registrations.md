# GET /accounts/{account_id}/devices/registrations

**Resource:** [Registrations](../resources/Registrations.md)
**List registrations**
**Operation ID:** `list-registrations`

Lists WARP registrations.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List of registrations response. |

## Security

- **api_token**

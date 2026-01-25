# GET /accounts/{account_id}/devices/registrations/{registration_id}

**Resource:** [Registrations](../resources/Registrations.md)
**Get registration**
**Operation ID:** `get-registration`

Fetches a single WARP registration.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `registration_id` | path | string | Yes |  |
| `account_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns a Registration. |

## Security

- **api_token**

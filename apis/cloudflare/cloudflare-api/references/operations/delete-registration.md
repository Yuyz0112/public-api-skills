# DELETE /accounts/{account_id}/devices/registrations/{registration_id}

**Resource:** [Registrations](../resources/Registrations.md)
**Delete registration**
**Operation ID:** `delete-registration`

Deletes a WARP registration.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `registration_id` | path | string | Yes |  |
| `account_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Registration deleted response. |

## Security

- **api_token**

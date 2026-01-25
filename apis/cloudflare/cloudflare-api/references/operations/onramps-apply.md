# POST /accounts/{account_id}/magic/cloud/onramps/{onramp_id}/apply

**Resource:** [On-ramps](../resources/On-ramps.md)
**Apply On-ramp**
**Operation ID:** `onramps-apply`

Apply an On-ramp (Closed Beta).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | mcn_account_id | Yes |  |
| `onramp_id` | path | mcn_onramp_id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 202 | Accepted. |
| 400 | Bad Request. |
| 401 | Invalid Credentials. |
| 403 | Forbidden. |
| 404 | Not Found. |
| 409 | Conflict. |
| 500 | Internal Server Error. |

## Security

- **api_email**
- **api_key**
- **api_token**

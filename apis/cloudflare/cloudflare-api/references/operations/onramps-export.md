# POST /accounts/{account_id}/magic/cloud/onramps/{onramp_id}/export

**Resource:** [On-ramps](../resources/On-ramps.md)
**Export as Terraform**
**Operation ID:** `onramps-export`

Export an On-ramp to terraform ready file(s) (Closed Beta).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | mcn_account_id | Yes |  |
| `onramp_id` | path | mcn_onramp_id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 201 | Exported file. |
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

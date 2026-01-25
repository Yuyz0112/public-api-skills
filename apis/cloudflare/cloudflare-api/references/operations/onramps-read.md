# GET /accounts/{account_id}/magic/cloud/onramps/{onramp_id}

**Resource:** [On-ramps](../resources/On-ramps.md)
**Read On-ramp**
**Operation ID:** `onramps-read`

Read an On-ramp (Closed Beta).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | mcn_account_id | Yes |  |
| `onramp_id` | path | mcn_onramp_id | Yes |  |
| `status` | query | boolean | No |  |
| `vpcs` | query | boolean | No |  |
| `post_apply_resources` | query | boolean | No |  |
| `planned_resources` | query | boolean | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK. |
| 400 | Bad Request. |
| 401 | Invalid Credentials. |
| 403 | Forbidden. |
| 404 | Not Found. |
| 500 | Internal Server Error. |

**Success Response Schema:**

[mcn_get_onramp_response](../schemas/mcn/mcn-get-onramp-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

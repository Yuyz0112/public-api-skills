# GET /accounts/{account_id}/magic/cloud/onramps

**Resource:** [On-ramps](../resources/On-ramps.md)
**List On-ramps**
**Operation ID:** `onramps-list`

List On-ramps (Closed Beta).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | mcn_account_id | Yes |  |
| `order_by` | query | string | No | One of ["updated_at", "id", "cloud_type", "name"]. |
| `desc` | query | boolean | No |  |
| `status` | query | boolean | No |  |
| `vpcs` | query | boolean | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK. |
| 400 | Bad Request. |
| 401 | Invalid Credentials. |
| 403 | Forbidden. |
| 500 | Internal Server Error. |

**Success Response Schema:**

[mcn_list_onramps_response](../schemas/mcn/mcn-list-onramps-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

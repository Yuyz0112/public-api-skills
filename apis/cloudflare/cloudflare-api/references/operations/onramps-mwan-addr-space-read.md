# GET /accounts/{account_id}/magic/cloud/onramps/magic_wan_address_space

**Resource:** [On-ramps](../resources/On-ramps.md)
**Read Magic WAN Address Space**
**Operation ID:** `onramps-mwan-addr-space-read`

Read the Magic WAN Address Space (Closed Beta).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | mcn_account_id | Yes |  |

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

[mcn_get_magic_wan_address_space_response](../schemas/mcn/mcn-get-magic-wan-address-space-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

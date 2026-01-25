# PUT /accounts/{account_id}/magic/cloud/onramps/magic_wan_address_space

**Resource:** [On-ramps](../resources/On-ramps.md)
**Update Magic WAN Address Space**
**Operation ID:** `onramps-mwan-addr-space-update`

Update the Magic WAN Address Space (Closed Beta).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | mcn_account_id | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [mcn_update_magic_wan_address_space_request](../schemas/mcn/mcn-update-magic-wan-address-space-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK. |
| 400 | Bad Request. |
| 401 | Invalid Credentials. |
| 403 | Forbidden. |
| 404 | Not Found. |
| 422 | Unprocessable Entity. |
| 500 | Internal Server Error. |

**Success Response Schema:**

[mcn_update_magic_wan_address_space_response](../schemas/mcn/mcn-update-magic-wan-address-space-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

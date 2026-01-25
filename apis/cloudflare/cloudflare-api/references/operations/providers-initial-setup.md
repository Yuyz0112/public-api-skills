# GET /accounts/{account_id}/magic/cloud/providers/{provider_id}/initial_setup

**Resource:** [Cloud Integrations](../resources/Cloud-Integrations.md)
**Get Cloud Integration Setup Config**
**Operation ID:** `providers-initial-setup`

Get initial configuration to complete Cloud Integration setup (Closed Beta).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | mcn_account_id | Yes |  |
| `provider_id` | path | mcn_provider_id | Yes |  |

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

[mcn_provider_initial_setup_response](../schemas/mcn/mcn-provider-initial-setup-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

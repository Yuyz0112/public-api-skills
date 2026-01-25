# GET /accounts/{account_id}/magic/cloud/providers

**Resource:** [Cloud Integrations](../resources/Cloud-Integrations.md)
**List Cloud Integrations**
**Operation ID:** `providers-list`

List Cloud Integrations (Closed Beta).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | mcn_account_id | Yes |  |
| `status` | query | boolean | No |  |
| `order_by` | query | string | No | One of ["updated_at", "id", "cloud_type", "name"]. |
| `desc` | query | boolean | No |  |
| `cloudflare` | query | boolean | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK. |
| 400 | Bad Request. |
| 401 | Invalid Credentials. |
| 403 | Forbidden. |
| 500 | Internal Server Error. |

**Success Response Schema:**

[mcn_read_account_providers_response](../schemas/mcn/mcn-read-account-providers-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

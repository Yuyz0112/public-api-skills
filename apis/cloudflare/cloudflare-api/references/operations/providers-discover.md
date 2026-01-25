# POST /accounts/{account_id}/magic/cloud/providers/{provider_id}/discover

**Resource:** [Cloud Integrations](../resources/Cloud-Integrations.md)
**Run Discovery**
**Operation ID:** `providers-discover`

Run discovery for a Cloud Integration (Closed Beta).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | mcn_account_id | Yes |  |
| `provider_id` | path | mcn_provider_id | Yes |  |
| `v2` | query | boolean | No |  |

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

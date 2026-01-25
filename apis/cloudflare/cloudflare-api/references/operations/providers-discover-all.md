# POST /accounts/{account_id}/magic/cloud/providers/discover

**Resource:** [Cloud Integrations](../resources/Cloud-Integrations.md)
**Run Discovery for All Integrations**
**Operation ID:** `providers-discover-all`

Run discovery for all Cloud Integrations in an account (Closed Beta).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | mcn_account_id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 202 | Accepted. |
| 400 | Bad Request. |
| 401 | Invalid Credentials. |
| 403 | Forbidden. |
| 409 | Conflict. |
| 500 | Internal Server Error. |

## Security

- **api_email**
- **api_key**
- **api_token**

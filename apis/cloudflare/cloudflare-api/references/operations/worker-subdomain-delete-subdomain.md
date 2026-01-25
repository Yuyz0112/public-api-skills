# DELETE /accounts/{account_id}/workers/subdomain

**Resource:** [Worker Subdomain](../resources/Worker-Subdomain.md)
**Delete Subdomain**
**Operation ID:** `worker-subdomain-delete-subdomain`

Deletes a Workers subdomain for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Subdomain deleted successfully. |
| 4XX | Delete Subdomain response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**

# DELETE /accounts/{account_id}/dlp/email/rules/{rule_id}

**Resource:** [DLP Email](../resources/DLP-Email.md)
**Delete email scanner rule**
**Operation ID:** `dlp-email-scanner-delete-rule`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `rule_id` | path | string (uuid) | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete Email Scanner Rule response. |
| 4XX | Delete Email Scanner Rule failure response. |

## Security

- **api_email**
- **api_key**
- **api_token**

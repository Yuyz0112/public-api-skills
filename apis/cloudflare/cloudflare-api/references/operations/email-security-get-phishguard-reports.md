# GET /accounts/{account_id}/email-security/phishguard/reports

**Resource:** [Email Security](../resources/Email-Security.md)
**Get `PhishGuard` reports**
**Operation ID:** `email_security_get_phishguard_reports`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | email-security_AccountId | Yes |  |
| `from_date` | query | string (date) | Yes |  |
| `to_date` | query | string (date) | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Contains a list of PhishGuard reports. |
| 4XX | (reference) |

## Security

- **api_email**
- **api_key**

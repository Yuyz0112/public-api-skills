# GET /accounts/{account_id}/email-security/settings/allow_policies/{policy_id}

**Resource:** [Email Security Settings](../resources/Email-Security-Settings.md)
**Get an email allow policy**
**Operation ID:** `email_security_get_allow_policy`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | email-security_AccountId | Yes |  |
| `policy_id` | path | email-security_AllowPolicyId | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 |  |
| 4XX | (reference) |

## Security

- **api_email**
- **api_key**

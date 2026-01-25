# GET /accounts/{account_id}/email-security/settings/allow_policies

**Resource:** [Email Security Settings](../resources/Email-Security-Settings.md)
**List email allow policies**
**Operation ID:** `email_security_list_allow_policies`

Lists, searches, and sorts an account’s email allow policies.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | email-security_AccountId | Yes |  |
| `page` | query | integer (int32) | No | The page number of paginated results. |
| `per_page` | query | integer (int32) | No | The number of results per page. |
| `order` | query | enum: pattern, created_at | No | The field to sort by. |
| `direction` | query | any | No | The sorting direction. |
| `search` | query | string | No | Allows searching in multiple properties of a record simultaneously.
This parameter is intended for human users, not automation. Its exact
behavior is intentionally left unspecified and is subject to change
in the future. |
| `is_sender` | query | boolean | No |  |
| `is_trusted_sender` | query | boolean | No |  |
| `is_recipient` | query | boolean | No |  |
| `is_exempt_recipient` | query | boolean | No |  |
| `is_spoof` | query | boolean | No |  |
| `is_acceptable_sender` | query | boolean | No |  |
| `verify_sender` | query | boolean | No |  |
| `pattern_type` | query | any | No |  |
| `pattern` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Contains a list of allow policies for the account. |
| 4XX | (reference) |

## Security

- **api_email**
- **api_key**

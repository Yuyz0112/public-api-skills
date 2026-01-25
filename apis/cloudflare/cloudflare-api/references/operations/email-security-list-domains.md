# GET /accounts/{account_id}/email-security/settings/domains

**Resource:** [Email Security Settings](../resources/Email-Security-Settings.md)
**List protected email domains**
**Operation ID:** `email_security_list_domains`

Lists, searches, and sorts an account’s email domains.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | email-security_AccountId | Yes |  |
| `page` | query | integer (int32) | No | The page number of paginated results. |
| `per_page` | query | integer (int32) | No | The number of results per page. |
| `order` | query | enum: domain, created_at | No | The field to sort by. |
| `direction` | query | any | No | The sorting direction. |
| `search` | query | string | No | Allows searching in multiple properties of a record simultaneously.
This parameter is intended for human users, not automation. Its exact
behavior is intentionally left unspecified and is subject to change
in the future. |
| `allowed_delivery_mode` | query | any | No | Filters response to domains with the provided delivery mode. |
| `domain` | query | string[] | No | Filters results by the provided domains, allowing for multiple occurrences. |
| `active_delivery_mode` | query | any | No | Filters response to domains with the currently active delivery mode. |
| `integration_id` | query | string (uuid) | No | Filters response to domains with the provided integration ID. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Contains a list of domains for the account. |
| 4XX | (reference) |

## Security

- **api_email**
- **api_key**

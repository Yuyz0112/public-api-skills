# GET /accounts/{account_id}/email-security/settings/impersonation_registry

**Resource:** [Email Security Settings](../resources/Email-Security-Settings.md)
**List entries in impersonation registry**
**Operation ID:** `email_security_list_display_names`

Lists, searches, and sorts entries in the impersonation registry.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | email-security_AccountId | Yes |  |
| `page` | query | integer (int32) | No | The page number of paginated results. |
| `per_page` | query | integer (int32) | No | The number of results per page. |
| `order` | query | enum: name, email, created_at | No | The field to sort by. |
| `direction` | query | any | No | The sorting direction. |
| `search` | query | string | No | Allows searching in multiple properties of a record simultaneously.
This parameter is intended for human users, not automation. Its exact
behavior is intentionally left unspecified and is subject to change
in the future. |
| `provenance` | query | any | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Contains the list of impersonation registry entries for the account. |
| 4XX | (reference) |

## Security

- **api_email**
- **api_key**

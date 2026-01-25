# GET /accounts/{account_id}/magic/advanced_dns_protection/configs/dns_protection/rules

**Resource:** [dos-flowtrackd-api_other](../resources/dos-flowtrackd-api-other.md)
**List all DNS Protection rules.**
**Operation ID:** `listDnsProtectionRulesForAccount`

List all DNS Protection rules for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | dos_identifier | Yes | The ID of the account. |
| `page` | query | integer (int64) | No | The page number for pagination. Defaults to 1. |
| `per_page` | query | integer (int64) | No | The number of items per page. Must be between 10 and 1000. Defaults to 25. |
| `order` | query | string | No | The field to order by. Defaults to 'prefix'. |
| `direction` | query | string | No | The direction of ordering (ASC or DESC). Defaults to 'ASC'. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List all DNS Protection rules response. |
| 4XX | List all DNS Protection rules failure. |

**Success Response Schema:**

[dos_dns-protection-rule-list-response](../schemas/dos/dos-dns-protection-rule-list-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
- **api_email**
- **api_key**

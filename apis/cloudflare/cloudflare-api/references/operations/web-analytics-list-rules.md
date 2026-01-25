# GET /accounts/{account_id}/rum/v2/{ruleset_id}/rules

**Resource:** [Web Analytics](../resources/Web-Analytics.md)
**List rules in Web Analytics ruleset**
**Operation ID:** `web-analytics-list-rules`

Lists all the rules in a Web Analytics ruleset.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | rum_identifier | Yes |  |
| `ruleset_id` | path | rum_ruleset_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List of Web Analytics rules in the ruleset. |
| 4XX | Failure response. |

**Success Response Schema:**

[rum_rules-response-collection](../schemas/rum/rum-rules-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**

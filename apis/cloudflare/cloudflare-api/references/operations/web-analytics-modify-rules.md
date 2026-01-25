# POST /accounts/{account_id}/rum/v2/{ruleset_id}/rules

**Resource:** [Web Analytics](../resources/Web-Analytics.md)
**Update Web Analytics rules**
**Operation ID:** `web-analytics-modify-rules`

Modifies one or more rules in a Web Analytics ruleset with a single request.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | rum_identifier | Yes |  |
| `ruleset_id` | path | rum_ruleset_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [rum_modify-rules-request](../schemas/rum/rum-modify-rules-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | List of modified Web Analytics rules. |
| 4XX | Failure response. |

**Success Response Schema:**

[rum_rules-response-collection](../schemas/rum/rum-rules-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**

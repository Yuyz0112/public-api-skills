# GET /zones/{zone_id}/email/routing/rules/catch_all

**Resource:** [Email Routing routing rules](../resources/Email-Routing-routing-rules.md)
**Get catch-all rule**
**Operation ID:** `email-routing-routing-rules-get-catch-all-rule`

Get information on the default catch-all routing rule.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | email_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get catch-all rule response |

**Success Response Schema:**

[email_catch_all_rule_response_single](../schemas/email/email-catch-all-rule-response-single.md)

## Security

- **api_email**
- **api_key**

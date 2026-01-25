# PUT /zones/{zone_id}/email/routing/rules/catch_all

**Resource:** [Email Routing routing rules](../resources/Email-Routing-routing-rules.md)
**Update catch-all rule**
**Operation ID:** `email-routing-routing-rules-update-catch-all-rule`

Enable or disable catch-all routing rule, or change action to forward to specific destination address.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | email_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [email_update_catch_all_rule_properties](../schemas/email/email-update-catch-all-rule-properties.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update catch-all rule response |

**Success Response Schema:**

[email_catch_all_rule_response_single](../schemas/email/email-catch-all-rule-response-single.md)

## Security

- **api_email**
- **api_key**

# PUT /zones/{zone_id}/email/routing/rules/{rule_identifier}

**Resource:** [Email Routing routing rules](../resources/Email-Routing-routing-rules.md)
**Update routing rule**
**Operation ID:** `email-routing-routing-rules-update-routing-rule`

Update actions and matches, or enable/disable specific routing rules.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `rule_identifier` | path | email_rule_identifier | Yes |  |
| `zone_id` | path | email_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [email_update_rule_properties](../schemas/email/email-update-rule-properties.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update routing rule response |

**Success Response Schema:**

[email_rule_response_single](../schemas/email/email-rule-response-single.md)

## Security

- **api_email**
- **api_key**

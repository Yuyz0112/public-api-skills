# GET /zones/{zone_id}/email/routing/rules/{rule_identifier}

**Resource:** [Email Routing routing rules](../resources/Email-Routing-routing-rules.md)
**Get routing rule**
**Operation ID:** `email-routing-routing-rules-get-routing-rule`

Get information for a specific routing rule already created.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `rule_identifier` | path | email_rule_identifier | Yes |  |
| `zone_id` | path | email_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get routing rule response |

**Success Response Schema:**

[email_rule_response_single](../schemas/email/email-rule-response-single.md)

## Security

- **api_email**
- **api_key**

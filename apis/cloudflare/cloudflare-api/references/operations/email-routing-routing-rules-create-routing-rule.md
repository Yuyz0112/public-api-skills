# POST /zones/{zone_id}/email/routing/rules

**Resource:** [Email Routing routing rules](../resources/Email-Routing-routing-rules.md)
**Create routing rule**
**Operation ID:** `email-routing-routing-rules-create-routing-rule`

Rules consist of a set of criteria for matching emails (such as an email being sent to a specific custom email address) plus a set of actions to take on the email (like forwarding it to a specific destination address).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | email_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [email_create_rule_properties](../schemas/email/email-create-rule-properties.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create routing rule response |

**Success Response Schema:**

[email_rule_response_single](../schemas/email/email-rule-response-single.md)

## Security

- **api_email**
- **api_key**

# GET /zones/{zone_id}/email/routing/rules

**Resource:** [Email Routing routing rules](../resources/Email-Routing-routing-rules.md)
**List routing rules**
**Operation ID:** `email-routing-routing-rules-list-routing-rules`

Lists existing routing rules.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | email_identifier | Yes |  |
| `page` | query | number | No |  |
| `per_page` | query | number | No |  |
| `enabled` | query | enum: true, false | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List routing rules response |

**Success Response Schema:**

[email_rules_response_collection](../schemas/email/email-rules-response-collection.md)

## Security

- **api_email**
- **api_key**

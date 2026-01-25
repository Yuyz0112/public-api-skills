# GET /zones/{zone_id}/email/routing

**Resource:** [Email Routing settings](../resources/Email-Routing-settings.md)
**Get Email Routing settings**
**Operation ID:** `email-routing-settings-get-email-routing-settings`

Get information about the settings for your Email Routing zone.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | email_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Email Routing settings response |

**Success Response Schema:**

[email_email_settings_response_single](../schemas/email/email-email-settings-response-single.md)

## Security

- **api_email**
- **api_key**

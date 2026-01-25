# POST /zones/{zone_id}/email/routing/disable

**Resource:** [Email Routing settings](../resources/Email-Routing-settings.md)
**Disable Email Routing**
**Operation ID:** `email-routing-settings-disable-email-routing`
⚠️ **Deprecated**

Disable your Email Routing zone. Also removes additional MX records previously required for Email Routing to work.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | email_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Disable Email Routing response |

**Success Response Schema:**

[email_email_settings_response_single](../schemas/email/email-email-settings-response-single.md)

## Security

- **api_email**
- **api_key**

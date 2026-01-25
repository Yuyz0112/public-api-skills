# POST /zones/{zone_id}/email/routing/dns

**Resource:** [Email Routing settings](../resources/Email-Routing-settings.md)
**Enable Email Routing**
**Operation ID:** `email-routing-settings-enable-email-routing-dns`

Enable you Email Routing zone. Add and lock the necessary MX and SPF records.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | email_identifier | Yes |  |

## Request Body

**Content Types:** `application/json`

**Schema:** [email_email_setting_dns_request_body](../schemas/email/email-email-setting-dns-request-body.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Enable Email Routing response |

**Success Response Schema:**

[email_email_settings_response_single](../schemas/email/email-email-settings-response-single.md)

## Security

- **api_email**
- **api_key**

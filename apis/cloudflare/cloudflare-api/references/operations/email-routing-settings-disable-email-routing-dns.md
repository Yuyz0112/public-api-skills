# DELETE /zones/{zone_id}/email/routing/dns

**Resource:** [Email Routing settings](../resources/Email-Routing-settings.md)
**Disable Email Routing**
**Operation ID:** `email-routing-settings-disable-email-routing-dns`

Disable your Email Routing zone. Also removes additional MX records previously required for Email Routing to work.

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
| 200 | Disable Email Routing response |

## Security

- **api_email**
- **api_key**

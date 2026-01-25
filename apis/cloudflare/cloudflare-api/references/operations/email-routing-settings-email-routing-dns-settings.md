# GET /zones/{zone_id}/email/routing/dns

**Resource:** [Email Routing settings](../resources/Email-Routing-settings.md)
**Email Routing - DNS settings**
**Operation ID:** `email-routing-settings-email-routing-dns-settings`

Show the DNS records needed to configure your Email Routing zone.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | email_identifier | Yes |  |
| `subdomain` | query | email_email_setting_name | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Email Routing - DNS settings response |

## Security

- **api_email**
- **api_key**

# PATCH /zones/{zone_id}/dns_settings

**Resource:** [DNS Settings for a Zone](../resources/DNS-Settings-for-a-Zone.md)
**Update DNS Settings**
**Operation ID:** `dns-settings-for-a-zone-update-dns-settings`

Update DNS settings for a zone

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | dns-settings_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dns-settings_dns-settings-zone-patch](../schemas/dns-settings/dns-settings-dns-settings-zone-patch.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Show DNS Settings response |
| 4XX | Show DNS Settings response failure |

**Success Response Schema:**

[dns-settings_schemas-dns_response_single](../schemas/dns-settings/dns-settings-schemas-dns-response-single.md)

## Security

- **api_token**
- **api_email**
- **api_key**

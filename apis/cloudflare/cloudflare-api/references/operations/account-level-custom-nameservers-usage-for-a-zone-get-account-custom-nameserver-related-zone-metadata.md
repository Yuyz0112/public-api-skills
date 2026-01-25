# GET /zones/{zone_id}/custom_ns

**Resource:** [Account-Level Custom Nameservers Usage for a Zone](../resources/Account-Level-Custom-Nameservers-Usage-for-a-Zone.md)
**Get Account Custom Nameserver Related Zone Metadata**
**Operation ID:** `account-level-custom-nameservers-usage-for-a-zone-get-account-custom-nameserver-related-zone-metadata`
⚠️ **Deprecated**

Get metadata for account-level custom nameservers on a zone.

Deprecated in favor of [Show DNS Settings](https://developers.cloudflare.com/api/operations/dns-settings-for-a-zone-list-dns-settings).


## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | dns-custom-nameservers_schemas-identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Account Custom Nameserver Related Zone Metadata response |
| 4XX | Get Account Custom Nameserver Related Zone Metadata response failure |

**Success Response Schema:**

[dns-custom-nameservers_get_response](../schemas/dns-custom-nameservers/dns-custom-nameservers-get-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**

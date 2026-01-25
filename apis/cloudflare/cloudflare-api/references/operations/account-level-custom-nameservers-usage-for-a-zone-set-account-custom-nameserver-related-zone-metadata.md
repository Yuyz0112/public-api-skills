# PUT /zones/{zone_id}/custom_ns

**Resource:** [Account-Level Custom Nameservers Usage for a Zone](../resources/Account-Level-Custom-Nameservers-Usage-for-a-Zone.md)
**Set Account Custom Nameserver Related Zone Metadata**
**Operation ID:** `account-level-custom-nameservers-usage-for-a-zone-set-account-custom-nameserver-related-zone-metadata`
⚠️ **Deprecated**

Set metadata for account-level custom nameservers on a zone.

If you would like new zones in the account to use account custom nameservers by default, use PUT /accounts/:identifier to set the account setting use_account_custom_ns_by_default to true.

Deprecated in favor of [Update DNS Settings](https://developers.cloudflare.com/api/operations/dns-settings-for-a-zone-update-dns-settings).


## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | dns-custom-nameservers_schemas-identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dns-custom-nameservers_zone_metadata](../schemas/dns-custom-nameservers/dns-custom-nameservers-zone-metadata.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Set Account Custom Nameserver Related Zone Metadata response |
| 4XX | Set Account Custom Nameserver Related Zone Metadata response failure |

**Success Response Schema:**

[dns-custom-nameservers_schemas-empty_response](../schemas/dns-custom-nameservers/dns-custom-nameservers-schemas-empty-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**

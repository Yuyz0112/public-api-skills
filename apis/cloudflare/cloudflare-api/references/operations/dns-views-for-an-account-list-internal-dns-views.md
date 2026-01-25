# GET /accounts/{account_id}/dns_settings/views

**Resource:** [DNS Internal Views for an Account](../resources/DNS-Internal-Views-for-an-Account.md)
**List Internal DNS Views**
**Operation ID:** `dns-views-for-an-account-list-internal-dns-views`

List DNS Internal Views for an Account

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | dns-settings_identifier | Yes |  |
| `name` | query | string | No |  |
| `name.exact` | query | string | No |  |
| `name.contains` | query | string | No |  |
| `name.startswith` | query | string | No |  |
| `name.endswith` | query | string | No |  |
| `zone_id` | query | string | No |  |
| `zone_name` | query | string | No |  |
| `match` | query | dns-settings_match | No |  |
| `page` | query | dns-settings_page | No |  |
| `per_page` | query | dns-settings_per_page | No |  |
| `order` | query | dns-settings_order | No |  |
| `direction` | query | dns-settings_direction | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Internal DNS Views response |
| 4XX | List Internal DNS Views response failure |

**Success Response Schema:**

[dns-settings_dns_view_response_collection](../schemas/dns-settings/dns-settings-dns-view-response-collection.md)

## Security

- **api_token**
- **api_email**
- **api_key**

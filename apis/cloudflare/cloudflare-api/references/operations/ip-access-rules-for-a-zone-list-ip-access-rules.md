# GET /zones/{zone_id}/firewall/access_rules/rules

**Resource:** [IP Access rules for a zone](../resources/IP-Access-rules-for-a-zone.md)
**List IP Access rules**
**Operation ID:** `ip-access-rules-for-a-zone-list-ip-access-rules`

Fetches IP Access rules of a zone. You can filter the results using several optional parameters.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | firewall_identifier | Yes |  |
| `mode` | query | firewall_schemas-mode | No |  |
| `configuration.target` | query | enum: ip, ip_range, asn... | No |  |
| `configuration.value` | query | string | No |  |
| `notes` | query | string | No |  |
| `match` | query | enum: any, all | No |  |
| `page` | query | number | No |  |
| `per_page` | query | number | No |  |
| `order` | query | enum: configuration.target, configuration.value, mode | No |  |
| `direction` | query | enum: asc, desc | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List IP Access rules response. |
| 4XX | List IP Access rules response failure. |

**Success Response Schema:**

[firewall_rule_collection_response](../schemas/firewall/firewall-rule-collection-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

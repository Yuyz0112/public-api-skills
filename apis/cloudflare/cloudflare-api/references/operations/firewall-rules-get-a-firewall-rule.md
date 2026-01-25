# GET /zones/{zone_id}/firewall/rules/{rule_id}

**Resource:** [Firewall rules](../resources/Firewall-rules.md)
**Get a firewall rule**
**Operation ID:** `firewall-rules-get-a-firewall-rule`
⚠️ **Deprecated**

Fetches the details of a firewall rule.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `rule_id` | path | firewall_firewall-rules_components-schemas-id | Yes |  |
| `zone_id` | path | firewall_identifier | Yes |  |
| `id` | query | any | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get a firewall rule response |
| 4XX | Get a firewall rule response failure |

**Success Response Schema:**

[firewall_filter-rules-single-response](../schemas/firewall/firewall-filter-rules-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

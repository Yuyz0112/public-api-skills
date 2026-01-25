# PUT /zones/{zone_id}/firewall/rules/{rule_id}

**Resource:** [Firewall rules](../resources/Firewall-rules.md)
**Update a firewall rule**
**Operation ID:** `firewall-rules-update-a-firewall-rule`
⚠️ **Deprecated**

Updates an existing firewall rule.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `rule_id` | path | firewall_firewall-rules_components-schemas-id | Yes |  |
| `zone_id` | path | firewall_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update a firewall rule response |
| 4XX | Update a firewall rule response failure |

**Success Response Schema:**

[firewall_filter-rules-single-response](../schemas/firewall/firewall-filter-rules-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

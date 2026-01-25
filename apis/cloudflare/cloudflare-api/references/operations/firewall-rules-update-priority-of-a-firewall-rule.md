# PATCH /zones/{zone_id}/firewall/rules/{rule_id}

**Resource:** [Firewall rules](../resources/Firewall-rules.md)
**Update priority of a firewall rule**
**Operation ID:** `firewall-rules-update-priority-of-a-firewall-rule`
⚠️ **Deprecated**

Updates the priority of an existing firewall rule.

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
| 200 | Update priority of a firewall rule response |
| 4XX | Update priority of a firewall rule response failure |

**Success Response Schema:**

[firewall_filter-rules-response-collection](../schemas/firewall/firewall-filter-rules-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**

# PUT /zones/{zone_id}/firewall/ua_rules/{ua_rule_id}

**Resource:** [User Agent Blocking rules](../resources/User-Agent-Blocking-rules.md)
**Update a User Agent Blocking rule**
**Operation ID:** `user-agent-blocking-rules-update-a-user-agent-blocking-rule`

Updates an existing User Agent Blocking rule.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `ua_rule_id` | path | firewall_components-ua-rule-id | Yes |  |
| `zone_id` | path | firewall_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update a User Agent Blocking rule response |
| 4XX | Update a User Agent Blocking rule response failure |

**Success Response Schema:**

[firewall_firewalluablock_response_single](../schemas/firewall/firewall-firewalluablock-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**

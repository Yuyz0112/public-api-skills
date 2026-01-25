# GET /zones/{zone_id}/firewall/ua_rules/{ua_rule_id}

**Resource:** [User Agent Blocking rules](../resources/User-Agent-Blocking-rules.md)
**Get a User Agent Blocking rule**
**Operation ID:** `user-agent-blocking-rules-get-a-user-agent-blocking-rule`

Fetches the details of a User Agent Blocking rule.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `ua_rule_id` | path | firewall_components-ua-rule-id | Yes |  |
| `zone_id` | path | firewall_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get a User Agent Blocking rule response |
| 4XX | Get a User Agent Blocking rule response failure |

**Success Response Schema:**

[firewall_firewalluablock_response_single](../schemas/firewall/firewall-firewalluablock-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**

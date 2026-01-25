# GET /zones/{zone_id}/firewall/ua_rules

**Resource:** [User Agent Blocking rules](../resources/User-Agent-Blocking-rules.md)
**List User Agent Blocking rules**
**Operation ID:** `user-agent-blocking-rules-list-user-agent-blocking-rules`

Fetches User Agent Blocking rules in a zone. You can filter the results using several optional parameters.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | firewall_identifier | Yes |  |
| `page` | query | number | No |  |
| `description` | query | any | No |  |
| `per_page` | query | number | No |  |
| `user_agent` | query | string | No |  |
| `paused` | query | boolean | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List User Agent Blocking rules response |
| 4XX | List User Agent Blocking rules response failure |

**Success Response Schema:**

[firewall_firewalluablock_response_collection](../schemas/firewall/firewall-firewalluablock-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**

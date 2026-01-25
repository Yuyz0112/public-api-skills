# POST /zones/{zone_id}/firewall/ua_rules

**Resource:** [User Agent Blocking rules](../resources/User-Agent-Blocking-rules.md)
**Create a User Agent Blocking rule**
**Operation ID:** `user-agent-blocking-rules-create-a-user-agent-blocking-rule`

Creates a new User Agent Blocking rule in a zone.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | firewall_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create a User Agent Blocking rule response |
| 4XX | Create a User Agent Blocking rule response failure |

**Success Response Schema:**

[firewall_firewalluablock_response_single](../schemas/firewall/firewall-firewalluablock-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**

# GET /zones/{zone_id}/firewall/lockdowns/{lock_downs_id}

**Resource:** [Zone Lockdown](../resources/Zone-Lockdown.md)
**Get a Zone Lockdown rule**
**Operation ID:** `zone-lockdown-get-a-zone-lockdown-rule`

Fetches the details of a Zone Lockdown rule.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `lock_downs_id` | path | firewall_lockdowns_components-schemas-id | Yes |  |
| `zone_id` | path | firewall_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get a Zone Lockdown rule response |
| 4XX | Get a Zone Lockdown rule response failure |

**Success Response Schema:**

[firewall_zonelockdown_response_single](../schemas/firewall/firewall-zonelockdown-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**

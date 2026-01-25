# PUT /zones/{zone_id}/firewall/lockdowns/{lock_downs_id}

**Resource:** [Zone Lockdown](../resources/Zone-Lockdown.md)
**Update a Zone Lockdown rule**
**Operation ID:** `zone-lockdown-update-a-zone-lockdown-rule`

Updates an existing Zone Lockdown rule.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `lock_downs_id` | path | firewall_lockdowns_components-schemas-id | Yes |  |
| `zone_id` | path | firewall_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update a Zone Lockdown rule response |
| 4XX | Update a Zone Lockdown rule response failure |

**Success Response Schema:**

[firewall_zonelockdown_response_single](../schemas/firewall/firewall-zonelockdown-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**

# POST /zones/{zone_id}/firewall/lockdowns

**Resource:** [Zone Lockdown](../resources/Zone-Lockdown.md)
**Create a Zone Lockdown rule**
**Operation ID:** `zone-lockdown-create-a-zone-lockdown-rule`

Creates a new Zone Lockdown rule.

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
| 200 | Create a Zone Lockdown rule response |
| 4XX | Create a Zone Lockdown rule response failure |

**Success Response Schema:**

[firewall_zonelockdown_response_single](../schemas/firewall/firewall-zonelockdown-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**

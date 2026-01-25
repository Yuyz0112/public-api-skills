# POST /zones/{zone_id}/firewall/access_rules/rules

**Resource:** [IP Access rules for a zone](../resources/IP-Access-rules-for-a-zone.md)
**Create an IP Access rule**
**Operation ID:** `ip-access-rules-for-a-zone-create-an-ip-access-rule`

Creates a new IP Access rule for a zone.

Note: To create an IP Access rule that applies to multiple zones, refer to [IP Access rules for a user](#ip-access-rules-for-a-user) or [IP Access rules for an account](#ip-access-rules-for-an-account) as appropriate.

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
| 200 | Create an IP Access rule response. |
| 4XX | Create an IP Access rule response failure. |

**Success Response Schema:**

[firewall_rule_single_response](../schemas/firewall/firewall-rule-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

# PATCH /user/firewall/access_rules/rules/{rule_id}

**Resource:** [IP Access rules for a user](../resources/IP-Access-rules-for-a-user.md)
**Update an IP Access rule**
**Operation ID:** `ip-access-rules-for-a-user-update-an-ip-access-rule`

Updates an IP Access rule defined at the user level. You can only update the rule action (`mode` parameter) and notes.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `rule_id` | path | firewall_rule_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update an IP Access rule response. |
| 4XX | Update an IP Access rule response failure. |

**Success Response Schema:**

[firewall_rule_single_response](../schemas/firewall/firewall-rule-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

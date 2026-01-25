# DELETE /user/firewall/access_rules/rules/{rule_id}

**Resource:** [IP Access rules for a user](../resources/IP-Access-rules-for-a-user.md)
**Delete an IP Access rule**
**Operation ID:** `ip-access-rules-for-a-user-delete-an-ip-access-rule`

Deletes an IP Access rule at the user level.

Note: Deleting a user-level rule will affect all zones owned by the user.

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
| 200 | Delete an IP Access rule response. |
| 4XX | Delete an IP Access rule response failure. |

**Success Response Schema:**

[firewall_rule_single_id_response](../schemas/firewall/firewall-rule-single-id-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

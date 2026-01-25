# DELETE /zones/{zone_id}/firewall/access_rules/rules/{rule_id}

**Resource:** [IP Access rules for a zone](../resources/IP-Access-rules-for-a-zone.md)
**Delete an IP Access rule**
**Operation ID:** `ip-access-rules-for-a-zone-delete-an-ip-access-rule`

Deletes an IP Access rule defined at the zone level.

Optionally, you can use the `cascade` property to specify that you wish to delete similar rules in other zones managed by the same zone owner.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | firewall_identifier | Yes |  |
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

# POST /user/firewall/access_rules/rules

**Resource:** [IP Access rules for a user](../resources/IP-Access-rules-for-a-user.md)
**Create an IP Access rule**
**Operation ID:** `ip-access-rules-for-a-user-create-an-ip-access-rule`

Creates a new IP Access rule for all zones owned by the current user.

Note: To create an IP Access rule that applies to a specific zone, refer to the [IP Access rules for a zone](#ip-access-rules-for-a-zone) endpoints.

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

# PATCH /accounts/{account_id}/firewall/access_rules/rules/{rule_id}

**Resource:** [IP Access rules for an account](../resources/IP-Access-rules-for-an-account.md)
**Update an IP Access rule**
**Operation ID:** `ip-access-rules-for-an-account-update-an-ip-access-rule`

Updates an IP Access rule defined at the account level.

Note: This operation will affect all zones in the account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `rule_id` | path | firewall_rule_identifier | Yes |  |
| `account_id` | path | firewall_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [firewall_schemas-rule](../schemas/firewall/firewall-schemas-rule.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update an IP Access rule response. |
| 4XX | Update an IP Access rule response failure. |

**Success Response Schema:**

[firewall_response_single](../schemas/firewall/firewall-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**

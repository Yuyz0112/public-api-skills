# DELETE /accounts/{account_id}/firewall/access_rules/rules/{rule_id}

**Resource:** [IP Access rules for an account](../resources/IP-Access-rules-for-an-account.md)
**Delete an IP Access rule**
**Operation ID:** `ip-access-rules-for-an-account-delete-an-ip-access-rule`

Deletes an existing IP Access rule defined at the account level.

Note: This operation will affect all zones in the account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `rule_id` | path | firewall_rule_identifier | Yes |  |
| `account_id` | path | firewall_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete an IP Access rule response. |
| 4XX | Delete an IP Access rule response failure. |

**Success Response Schema:**

[firewall_api-response-single-id](../schemas/firewall/firewall-api-response-single-id.md)

## Security

- **api_email**
- **api_key**
- **api_token**

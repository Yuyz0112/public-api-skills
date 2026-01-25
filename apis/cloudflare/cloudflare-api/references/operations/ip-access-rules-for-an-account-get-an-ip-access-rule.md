# GET /accounts/{account_id}/firewall/access_rules/rules/{rule_id}

**Resource:** [IP Access rules for an account](../resources/IP-Access-rules-for-an-account.md)
**Get an IP Access rule**
**Operation ID:** `ip-access-rules-for-an-account-get-an-ip-access-rule`

Fetches the details of an IP Access rule defined at the account level.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `rule_id` | path | firewall_rule_identifier | Yes |  |
| `account_id` | path | firewall_account_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get an IP Access rule response. |
| 4XX | Get an IP Access rule response failure. |

**Success Response Schema:**

[firewall_response_single](../schemas/firewall/firewall-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**

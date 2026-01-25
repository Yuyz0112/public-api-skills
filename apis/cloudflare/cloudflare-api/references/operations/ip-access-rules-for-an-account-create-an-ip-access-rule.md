# POST /accounts/{account_id}/firewall/access_rules/rules

**Resource:** [IP Access rules for an account](../resources/IP-Access-rules-for-an-account.md)
**Create an IP Access rule**
**Operation ID:** `ip-access-rules-for-an-account-create-an-ip-access-rule`

Creates a new IP Access rule for an account. The rule will apply to all zones in the account.

Note: To create an IP Access rule that applies to a single zone, refer to the [IP Access rules for a zone](#ip-access-rules-for-a-zone) endpoints.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | firewall_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create an IP Access rule response. |
| 4XX | Create an IP Access rule response failure. |

**Success Response Schema:**

[firewall_response_single](../schemas/firewall/firewall-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**

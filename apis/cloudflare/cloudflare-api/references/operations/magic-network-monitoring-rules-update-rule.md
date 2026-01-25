# PATCH /accounts/{account_id}/mnm/rules/{rule_id}

**Resource:** [Magic Network Monitoring Rules](../resources/Magic-Network-Monitoring-Rules.md)
**Update rule**
**Operation ID:** `magic-network-monitoring-rules-update-rule`

Update a network monitoring rule for account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `rule_id` | path | magic-visibility-mnm_rule_identifier | Yes |  |
| `account_id` | path | magic-visibility-mnm_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update rule response |
| 4XX | Update rule response failure |

**Success Response Schema:**

[magic-visibility-mnm_mnm_rules_single_response](../schemas/magic-visibility-mnm/magic-visibility-mnm-mnm-rules-single-response.md)

## Security

- **api_email**
- **api_key**

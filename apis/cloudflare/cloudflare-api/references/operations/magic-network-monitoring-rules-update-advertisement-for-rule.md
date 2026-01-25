# PATCH /accounts/{account_id}/mnm/rules/{rule_id}/advertisement

**Resource:** [Magic Network Monitoring Rules](../resources/Magic-Network-Monitoring-Rules.md)
**Update advertisement for rule**
**Operation ID:** `magic-network-monitoring-rules-update-advertisement-for-rule`

Update advertisement for rule.

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
| 200 | Update advertisement for rule response |
| 4XX | Update advertisement for rule response failure |

**Success Response Schema:**

[magic-visibility-mnm_mnm_rule_advertisement_single_response](../schemas/magic-visibility-mnm/magic-visibility-mnm-mnm-rule-advertisement-single-response.md)

## Security

- **api_email**
- **api_key**

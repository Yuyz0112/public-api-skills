# PUT /accounts/{account_id}/mnm/rules

**Resource:** [Magic Network Monitoring Rules](../resources/Magic-Network-Monitoring-Rules.md)
**Update rules**
**Operation ID:** `magic-network-monitoring-rules-update-rules`

Update network monitoring rules for account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | magic-visibility-mnm_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update rules response |
| 4XX | Update rules response failure |

**Success Response Schema:**

[magic-visibility-mnm_mnm_rules_single_response](../schemas/magic-visibility-mnm/magic-visibility-mnm-mnm-rules-single-response.md)

## Security

- **api_email**
- **api_key**

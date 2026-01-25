# POST /accounts/{account_id}/mnm/rules

**Resource:** [Magic Network Monitoring Rules](../resources/Magic-Network-Monitoring-Rules.md)
**Create rules**
**Operation ID:** `magic-network-monitoring-rules-create-rules`

Create network monitoring rules for account. Currently only supports creating a single rule per API request.

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
| 200 | Create rules response |
| 4XX | Create rules response failure |

**Success Response Schema:**

[magic-visibility-mnm_mnm_rules_single_response](../schemas/magic-visibility-mnm/magic-visibility-mnm-mnm-rules-single-response.md)

## Security

- **api_email**
- **api_key**

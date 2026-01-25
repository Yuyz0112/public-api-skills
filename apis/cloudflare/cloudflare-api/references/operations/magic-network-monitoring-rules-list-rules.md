# GET /accounts/{account_id}/mnm/rules

**Resource:** [Magic Network Monitoring Rules](../resources/Magic-Network-Monitoring-Rules.md)
**List rules**
**Operation ID:** `magic-network-monitoring-rules-list-rules`

Lists network monitoring rules for account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | magic-visibility-mnm_account_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List rules response |
| 4XX | List rules response failure |

**Success Response Schema:**

[magic-visibility-mnm_mnm_rules_collection_response](../schemas/magic-visibility-mnm/magic-visibility-mnm-mnm-rules-collection-response.md)

## Security

- **api_email**
- **api_key**

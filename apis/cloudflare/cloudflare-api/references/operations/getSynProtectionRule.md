# GET /accounts/{account_id}/magic/advanced_tcp_protection/configs/syn_protection/rules/{rule_id}

**Resource:** [dos-flowtrackd-api_other](../resources/dos-flowtrackd-api-other.md)
**Get SYN Protection rule.**
**Operation ID:** `getSynProtectionRule`

Get a SYN Protection rule specified by the given UUID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | dos_identifier | Yes | The ID of the account. |
| `rule_id` | path | dos_uuid | Yes | The UUID of the SYN Protection rule. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get SYN Protection rule response. |
| 4XX | Get SYN Protection rule failure. |

**Success Response Schema:**

[dos_syn-protection-rule-response](../schemas/dos/dos-syn-protection-rule-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
- **api_email**
- **api_key**

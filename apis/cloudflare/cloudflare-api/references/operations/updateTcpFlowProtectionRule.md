# PATCH /accounts/{account_id}/magic/advanced_tcp_protection/configs/tcp_flow_protection/rules/{rule_id}

**Resource:** [dos-flowtrackd-api_other](../resources/dos-flowtrackd-api-other.md)
**Update TCP Flow Protection rule.**
**Operation ID:** `updateTcpFlowProtectionRule`

Update a TCP Flow Protection rule specified by the given UUID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | dos_identifier | Yes | The ID of the account. |
| `rule_id` | path | dos_uuid | Yes | The UUID of the TCP Flow Protection rule to update. |

## Request Body

The updates to apply to the TCP Flow Protection rule.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dos_TcpFlowProtectionRuleUpdate](../schemas/dos/dos-TcpFlowProtectionRuleUpdate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update TCP Flow Protection rule response. |
| 4XX | Update TCP Flow Protection rule failure. |

**Success Response Schema:**

[dos_tcp-flow-protection-rule-response](../schemas/dos/dos-tcp-flow-protection-rule-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
- **api_email**
- **api_key**

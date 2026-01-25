# POST /accounts/{account_id}/magic/advanced_tcp_protection/configs/tcp_flow_protection/rules

**Resource:** [dos-flowtrackd-api_other](../resources/dos-flowtrackd-api-other.md)
**Create TCP Flow Protection rule.**
**Operation ID:** `createTcpFlowProtectionRule`

Create a TCP Flow Protection rule for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | dos_identifier | Yes | The ID of the account. |

## Request Body

The new TCP Flow Protection rule.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dos_NewTcpFlowProtectionRule](../schemas/dos/dos-NewTcpFlowProtectionRule.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create TCP Flow Protection rule response. |
| 4XX | Create TCP Flow Protection rule failure. |

**Success Response Schema:**

[dos_tcp-flow-protection-rule-response](../schemas/dos/dos-tcp-flow-protection-rule-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
- **api_email**
- **api_key**

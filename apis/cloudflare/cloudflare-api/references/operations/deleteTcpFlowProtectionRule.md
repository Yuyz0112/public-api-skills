# DELETE /accounts/{account_id}/magic/advanced_tcp_protection/configs/tcp_flow_protection/rules/{rule_id}

**Resource:** [dos-flowtrackd-api_other](../resources/dos-flowtrackd-api-other.md)
**Delete TCP Flow Protection rule.**
**Operation ID:** `deleteTcpFlowProtectionRule`

Delete a TCP Flow Protection rule specified by the given UUID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | dos_identifier | Yes | The ID of the account. |
| `rule_id` | path | dos_uuid | Yes | The UUID of the TCP Flow Protection rule to delete. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete TCP Flow Protection rule response. |
| 4XX | Delete TCP Flow Protection rule failure. |

**Success Response Schema:**

[dos_api-response-common](../schemas/dos/dos-api-response-common.md)

## Security

- **api_token**
- **api_email**
- **api_key**
- **api_email**
- **api_key**

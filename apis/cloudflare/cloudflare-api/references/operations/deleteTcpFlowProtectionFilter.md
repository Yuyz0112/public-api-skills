# DELETE /accounts/{account_id}/magic/advanced_tcp_protection/configs/tcp_flow_protection/filters/{filter_id}

**Resource:** [dos-flowtrackd-api_other](../resources/dos-flowtrackd-api-other.md)
**Delete TCP Flow Protection filter.**
**Operation ID:** `deleteTcpFlowProtectionFilter`

Delete a TCP Flow Protection filter specified by the given UUID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | dos_identifier | Yes | The ID of the account. |
| `filter_id` | path | dos_uuid | Yes | The UUID of the filter to delete. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete TCP Flow Protection filter response. |
| 4XX | Delete TCP Flow Protection filter failure. |

**Success Response Schema:**

[dos_api-response-common](../schemas/dos/dos-api-response-common.md)

## Security

- **api_token**
- **api_email**
- **api_key**
- **api_email**
- **api_key**

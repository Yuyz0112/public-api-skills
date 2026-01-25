# GET /accounts/{account_id}/magic/advanced_tcp_protection/configs/tcp_flow_protection/filters/{filter_id}

**Resource:** [dos-flowtrackd-api_other](../resources/dos-flowtrackd-api-other.md)
**Get TCP Flow Protection filter.**
**Operation ID:** `getTcpFlowProtectionFilter`

Get a TCP Flow Protection filter specified by the given UUID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | dos_identifier | Yes | The ID of the account. |
| `filter_id` | path | dos_uuid | Yes | The UUID of the filter to retrieve. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get TCP Flow Protection filter response. |
| 4XX | Get TCP Flow Protection filter failure. |

**Success Response Schema:**

[dos_expression-filter-response](../schemas/dos/dos-expression-filter-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
- **api_email**
- **api_key**

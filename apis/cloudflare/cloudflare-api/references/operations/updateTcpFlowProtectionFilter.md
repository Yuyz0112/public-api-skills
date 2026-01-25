# PATCH /accounts/{account_id}/magic/advanced_tcp_protection/configs/tcp_flow_protection/filters/{filter_id}

**Resource:** [dos-flowtrackd-api_other](../resources/dos-flowtrackd-api-other.md)
**Update TCP Flow Protection filter.**
**Operation ID:** `updateTcpFlowProtectionFilter`

Update a TCP Flow Protection filter specified by the given UUID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | dos_identifier | Yes | The ID of the account. |
| `filter_id` | path | dos_uuid | Yes | The UUID of the filter to update. |

## Request Body

The updates to apply to the filter.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [dos_ExpressionFilterUpdate](../schemas/dos/dos-ExpressionFilterUpdate.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update TCP Flow Protection filter response. |
| 4XX | Update TCP Flow Protection filter failure. |

**Success Response Schema:**

[dos_expression-filter-response](../schemas/dos/dos-expression-filter-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
- **api_email**
- **api_key**

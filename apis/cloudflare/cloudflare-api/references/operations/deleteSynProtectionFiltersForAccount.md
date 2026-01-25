# DELETE /accounts/{account_id}/magic/advanced_tcp_protection/configs/syn_protection/filters

**Resource:** [dos-flowtrackd-api_other](../resources/dos-flowtrackd-api-other.md)
**Delete all SYN Protection filters.**
**Operation ID:** `deleteSynProtectionFiltersForAccount`

Delete all SYN Protection filters for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | dos_identifier | Yes | The ID of the account. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete all SYN Protection filters response. |
| 4XX | Delete all SYN Protection filters failure. |

**Success Response Schema:**

[dos_api-response-common](../schemas/dos/dos-api-response-common.md)

## Security

- **api_token**
- **api_email**
- **api_key**
- **api_email**
- **api_key**

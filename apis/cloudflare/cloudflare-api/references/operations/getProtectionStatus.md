# GET /accounts/{account_id}/magic/advanced_tcp_protection/configs/tcp_protection_status

**Resource:** [dos-flowtrackd-api_other](../resources/dos-flowtrackd-api-other.md)
**Get protection status.**
**Operation ID:** `getProtectionStatus`

Get the protection status of the account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | dos_identifier | Yes | The account ID. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get protection status response. |
| 4XX | Get protection status failure. |

**Success Response Schema:**

[dos_protection-status-response](../schemas/dos/dos-protection-status-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
- **api_email**
- **api_key**

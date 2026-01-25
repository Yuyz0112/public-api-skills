# DELETE /accounts/{account_id}/magic/advanced_tcp_protection/configs/allowlist

**Resource:** [dos-flowtrackd-api_other](../resources/dos-flowtrackd-api-other.md)
**Delete all allowlist prefixes.**
**Operation ID:** `deleteAllowlistPrefixesForAccount`

Delete all allowlist prefixes for an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | dos_identifier | Yes | The ID of the account. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete all allowlist prefixes response. |
| 4XX | Delete all allowlist prefixes failure. |

**Success Response Schema:**

[dos_api-response-common](../schemas/dos/dos-api-response-common.md)

## Security

- **api_token**
- **api_email**
- **api_key**
- **api_email**
- **api_key**

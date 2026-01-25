# GET /accounts/{account_id}/magic/advanced_tcp_protection/configs/allowlist/{prefix_id}

**Resource:** [dos-flowtrackd-api_other](../resources/dos-flowtrackd-api-other.md)
**Get allowlist prefix.**
**Operation ID:** `getAllowlistPrefix`

Get an allowlist prefix specified by the given UUID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | dos_identifier | Yes | The ID of the account. |
| `prefix_id` | path | dos_uuid | Yes | The UUID of the allowlist prefix. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get allowlist prefix response. |
| 4XX | Get allowlist prefix failure. |

**Success Response Schema:**

[dos_infra-prefix-response](../schemas/dos/dos-infra-prefix-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
- **api_email**
- **api_key**

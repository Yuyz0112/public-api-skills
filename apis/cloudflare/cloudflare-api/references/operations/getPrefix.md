# GET /accounts/{account_id}/magic/advanced_tcp_protection/configs/prefixes/{prefix_id}

**Resource:** [dos-flowtrackd-api_other](../resources/dos-flowtrackd-api-other.md)
**Get prefix.**
**Operation ID:** `getPrefix`

Get a prefix specified by the given UUID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | dos_identifier | Yes | The ID of the account. |
| `prefix_id` | path | dos_uuid | Yes | The UUID of the prefix. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get prefix response. |
| 4XX | Get prefix failure. |

**Success Response Schema:**

[dos_prefix-response](../schemas/dos/dos-prefix-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
- **api_email**
- **api_key**

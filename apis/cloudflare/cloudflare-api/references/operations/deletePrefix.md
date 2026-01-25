# DELETE /accounts/{account_id}/magic/advanced_tcp_protection/configs/prefixes/{prefix_id}

**Resource:** [dos-flowtrackd-api_other](../resources/dos-flowtrackd-api-other.md)
**Delete prefix.**
**Operation ID:** `deletePrefix`

Delete the prefix for an account given a UUID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | dos_identifier | Yes | The ID of the account. |
| `prefix_id` | path | dos_uuid | Yes | The UUID of the prefix to delete. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete prefix response. |
| 4XX | Delete prefix failure. |

**Success Response Schema:**

[dos_api-response-common](../schemas/dos/dos-api-response-common.md)

## Security

- **api_token**
- **api_email**
- **api_key**
- **api_email**
- **api_key**

# GET /accounts/{account_id}/stream/storage-usage

**Resource:** [Stream Videos](../resources/Stream-Videos.md)
**Storage use**
**Operation ID:** `stream-videos-storage-usage`

Returns information about an account's storage use.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | stream_account_identifier | Yes |  |
| `creator` | query | stream_creator | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns information about an account's storage use response. |
| 4XX | Returns information about an account's storage use response failure. |

**Success Response Schema:**

[stream_storage_use_response](../schemas/stream/stream-storage-use-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

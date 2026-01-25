# GET /accounts/{account_id}/stream/keys

**Resource:** [Stream Signing Keys](../resources/Stream-Signing-Keys.md)
**List signing keys**
**Operation ID:** `stream-signing-keys-list-signing-keys`

Lists the video ID and creation date and time when a signing key was created.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | stream_schemas-identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List signing keys response. |
| 4XX | List signing keys response failure. |

**Success Response Schema:**

[stream_key_response_collection](../schemas/stream/stream-key-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**

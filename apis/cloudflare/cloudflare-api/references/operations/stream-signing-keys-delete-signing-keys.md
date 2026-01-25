# DELETE /accounts/{account_id}/stream/keys/{identifier}

**Resource:** [Stream Signing Keys](../resources/Stream-Signing-Keys.md)
**Delete signing keys**
**Operation ID:** `stream-signing-keys-delete-signing-keys`

Deletes signing keys and revokes all signed URLs generated with the key.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `identifier` | path | stream_schemas-identifier | Yes |  |
| `account_id` | path | stream_schemas-identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete signing keys response. |
| 4XX | Delete signing keys response failure. |

**Success Response Schema:**

[stream_deleted_response](../schemas/stream/stream-deleted-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

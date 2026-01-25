# POST /accounts/{account_id}/stream/keys

**Resource:** [Stream Signing Keys](../resources/Stream-Signing-Keys.md)
**Create signing keys**
**Operation ID:** `stream-signing-keys-create-signing-keys`

Creates an RSA private key in PEM and JWK formats. Key files are only displayed once after creation. Keys are created, used, and deleted independently of videos, and every key can sign any video.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | stream_schemas-identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create signing keys response. |
| 4XX | Create signing keys response failure. |

**Success Response Schema:**

[stream_key_generation_response](../schemas/stream/stream-key-generation-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**

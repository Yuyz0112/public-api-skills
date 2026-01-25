# POST /accounts/{account_id}/stream/live_inputs

**Resource:** [Stream Live Inputs](../resources/Stream-Live-Inputs.md)
**Create a live input**
**Operation ID:** `stream-live-inputs-create-a-live-input`

Creates a live input, and returns credentials that you or your users can use to stream live video to Cloudflare Stream.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | stream_schemas-identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [stream_create_input_request](../schemas/stream/stream-create-input-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create a live input response. |
| 4XX | Create a live input response failure. |

**Success Response Schema:**

[stream_live_input_response_single](../schemas/stream/stream-live-input-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**

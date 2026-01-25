# PUT /accounts/{account_id}/stream/live_inputs/{live_input_identifier}

**Resource:** [Stream Live Inputs](../resources/Stream-Live-Inputs.md)
**Update a live input**
**Operation ID:** `stream-live-inputs-update-a-live-input`

Updates a specified live input.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `live_input_identifier` | path | stream_live_input_identifier | Yes |  |
| `account_id` | path | stream_schemas-identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [stream_update_input_request](../schemas/stream/stream-update-input-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update a live input response. |
| 4XX | Update a live input response failure. |

**Success Response Schema:**

[stream_live_input_response_single](../schemas/stream/stream-live-input-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**

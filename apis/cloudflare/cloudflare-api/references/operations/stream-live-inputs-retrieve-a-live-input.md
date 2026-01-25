# GET /accounts/{account_id}/stream/live_inputs/{live_input_identifier}

**Resource:** [Stream Live Inputs](../resources/Stream-Live-Inputs.md)
**Retrieve a live input**
**Operation ID:** `stream-live-inputs-retrieve-a-live-input`

Retrieves details of an existing live input.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `live_input_identifier` | path | stream_live_input_identifier | Yes |  |
| `account_id` | path | stream_schemas-identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Retrieve a live input response. |
| 4XX | Retrieve a live input response failure. |

**Success Response Schema:**

[stream_live_input_response_single](../schemas/stream/stream-live-input-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**

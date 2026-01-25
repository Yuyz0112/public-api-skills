# GET /accounts/{account_id}/stream/live_inputs/{live_input_identifier}/outputs

**Resource:** [Stream Live Inputs](../resources/Stream-Live-Inputs.md)
**List all outputs associated with a specified live input**
**Operation ID:** `stream-live-inputs-list-all-outputs-associated-with-a-specified-live-input`

Retrieves all outputs associated with a specified live input.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `live_input_identifier` | path | stream_live_input_identifier | Yes |  |
| `account_id` | path | stream_schemas-identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List all outputs associated with a specified live input response. |
| 4XX | List all outputs associated with a specified live input response failure. |

**Success Response Schema:**

[stream_output_response_collection](../schemas/stream/stream-output-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**

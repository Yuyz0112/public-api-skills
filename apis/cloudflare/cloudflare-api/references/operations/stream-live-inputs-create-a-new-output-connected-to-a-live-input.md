# POST /accounts/{account_id}/stream/live_inputs/{live_input_identifier}/outputs

**Resource:** [Stream Live Inputs](../resources/Stream-Live-Inputs.md)
**Create a new output, connected to a live input**
**Operation ID:** `stream-live-inputs-create-a-new-output,-connected-to-a-live-input`

Creates a new output that can be used to simulcast or restream live video to other RTMP or SRT destinations. Outputs are always linked to a specific live input — one live input can have many outputs.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `live_input_identifier` | path | stream_live_input_identifier | Yes |  |
| `account_id` | path | stream_schemas-identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [stream_create_output_request](../schemas/stream/stream-create-output-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create a new output, connected to a live input response. |
| 4XX | Create a new output, connected to a live input response failure. |

**Success Response Schema:**

[stream_output_response_single](../schemas/stream/stream-output-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**

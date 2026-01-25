# PUT /accounts/{account_id}/stream/live_inputs/{live_input_identifier}/outputs/{output_identifier}

**Resource:** [Stream Live Inputs](../resources/Stream-Live-Inputs.md)
**Update an output**
**Operation ID:** `stream-live-inputs-update-an-output`

Updates the state of an output.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `output_identifier` | path | stream_output_identifier | Yes |  |
| `live_input_identifier` | path | stream_live_input_identifier | Yes |  |
| `account_id` | path | stream_schemas-identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [stream_update_output_request](../schemas/stream/stream-update-output-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update an output response. |
| 4XX | Update an output response failure. |

**Success Response Schema:**

[stream_output_response_single](../schemas/stream/stream-output-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**

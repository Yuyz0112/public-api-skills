# GET /accounts/{account_id}/stream/live_inputs

**Resource:** [Stream Live Inputs](../resources/Stream-Live-Inputs.md)
**List live inputs**
**Operation ID:** `stream-live-inputs-list-live-inputs`

Lists the live inputs created for an account. To get the credentials needed to stream to a specific live input, request a single live input.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | stream_schemas-identifier | Yes |  |
| `include_counts` | query | stream_include_counts | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List live inputs response. |
| 4XX | List live inputs response failure. |

**Success Response Schema:**

[stream_live_input_response_collection](../schemas/stream/stream-live-input-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**

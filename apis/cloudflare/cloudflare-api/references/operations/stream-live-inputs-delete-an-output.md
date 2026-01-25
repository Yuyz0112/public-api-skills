# DELETE /accounts/{account_id}/stream/live_inputs/{live_input_identifier}/outputs/{output_identifier}

**Resource:** [Stream Live Inputs](../resources/Stream-Live-Inputs.md)
**Delete an output**
**Operation ID:** `stream-live-inputs-delete-an-output`

Deletes an output and removes it from the associated live input.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `output_identifier` | path | stream_output_identifier | Yes |  |
| `live_input_identifier` | path | stream_live_input_identifier | Yes |  |
| `account_id` | path | stream_schemas-identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete an output response. |
| 4XX | Delete an output response failure. |

## Security

- **api_email**
- **api_key**
- **api_token**

# DELETE /accounts/{account_id}/stream/live_inputs/{live_input_identifier}

**Resource:** [Stream Live Inputs](../resources/Stream-Live-Inputs.md)
**Delete a live input**
**Operation ID:** `stream-live-inputs-delete-a-live-input`

Prevents a live input from being streamed to and makes the live input inaccessible to any future API calls.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `live_input_identifier` | path | stream_live_input_identifier | Yes |  |
| `account_id` | path | stream_schemas-identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete a live input response. |
| 4XX | Delete a live input response failure. |

## Security

- **api_email**
- **api_key**
- **api_token**

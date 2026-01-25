# DELETE /accounts/{account_id}/calls/turn_keys/{key_id}

**Resource:** [Calls TURN Keys](../resources/Calls-TURN-Keys.md)
**Delete TURN key**
**Operation ID:** `calls-delete-turn-key`

Deletes a TURN key from Cloudflare Calls

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `key_id` | path | calls_identifier | Yes |  |
| `account_id` | path | calls_account_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete TURN key response |
| 4XX | Delete TURN key response failure |

**Success Response Schema:**

[calls_turn_key_response_single](../schemas/calls/calls-turn-key-response-single.md)

## Security

- **api_token**

# GET /accounts/{account_id}/calls/turn_keys/{key_id}

**Resource:** [Calls TURN Keys](../resources/Calls-TURN-Keys.md)
**Retrieve TURN key details**
**Operation ID:** `calls-retrieve-turn-key-details`

Fetches details for a single TURN key.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `key_id` | path | calls_identifier | Yes |  |
| `account_id` | path | calls_account_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Retrieve TURN key details response |
| 4XX | Retrieve TURN key details failure |

**Success Response Schema:**

[calls_turn_key_response_single](../schemas/calls/calls-turn-key-response-single.md)

## Security

- **api_token**

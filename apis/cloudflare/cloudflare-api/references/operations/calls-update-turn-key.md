# PUT /accounts/{account_id}/calls/turn_keys/{key_id}

**Resource:** [Calls TURN Keys](../resources/Calls-TURN-Keys.md)
**Edit TURN key details**
**Operation ID:** `calls-update-turn-key`

Edit details for a single TURN key.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `key_id` | path | calls_identifier | Yes |  |
| `account_id` | path | calls_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [calls_turn_key_editable_fields](../schemas/calls/calls-turn-key-editable-fields.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Edit TURN key details response |
| 4XX | Edit TURN key details response failure |

**Success Response Schema:**

[calls_turn_key_response_single](../schemas/calls/calls-turn-key-response-single.md)

## Security

- **api_token**

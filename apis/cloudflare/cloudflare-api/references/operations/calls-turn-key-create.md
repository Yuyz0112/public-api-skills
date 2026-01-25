# POST /accounts/{account_id}/calls/turn_keys

**Resource:** [Calls TURN Keys](../resources/Calls-TURN-Keys.md)
**Create a new TURN key**
**Operation ID:** `calls-turn-key-create`

Creates a new Cloudflare Calls TURN key.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | calls_account_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [calls_turn_key_editable_fields](../schemas/calls/calls-turn-key-editable-fields.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created a new TURN key |

**Success Response Schema:**

[calls_turn_key_single_with_secret](../schemas/calls/calls-turn-key-single-with-secret.md)

## Security

- **api_token**

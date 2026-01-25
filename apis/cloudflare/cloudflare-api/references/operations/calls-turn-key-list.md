# GET /accounts/{account_id}/calls/turn_keys

**Resource:** [Calls TURN Keys](../resources/Calls-TURN-Keys.md)
**List TURN Keys**
**Operation ID:** `calls-turn-key-list`

Lists all TURN keys in the Cloudflare account

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | calls_account_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List TURN key response |
| 4XX | List TURN key response failure |

**Success Response Schema:**

[calls_turn_key_collection](../schemas/calls/calls-turn-key-collection.md)

## Security

- **api_token**

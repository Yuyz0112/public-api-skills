# issuing_network_token_mastercard

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `card_reference_id` | string | No | A unique reference ID from MasterCard to represent the card account number. |
| `token_reference_id` | string | Yes | The network-unique identifier for the token. |
| `token_requestor_id` | string | Yes | The ID of the entity requesting tokenization, specific to MasterCard. |
| `token_requestor_name` | string | No | The name of the entity requesting tokenization, if known. This is directly provided from MasterCard. |


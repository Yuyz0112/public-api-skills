# issuing_network_token_wallet_provider

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account_id` | string | No | The wallet provider-given account ID of the digital wallet the token belongs to. |
| `account_trust_score` | integer | No | An evaluation on the trustworthiness of the wallet account between 1 and 5. A higher score indicates more trustworthy. |
| `card_number_source` | enum: app, manual, on_file... | No | The method used for tokenizing a card. |
| `cardholder_address` | [issuing_network_token_address](issuing-network-token-address.md) | No |  |
| `cardholder_name` | string | No | The name of the cardholder tokenizing the card. |
| `device_trust_score` | integer | No | An evaluation on the trustworthiness of the device. A higher score indicates more trustworthy. |
| `hashed_account_email_address` | string | No | The hashed email address of the cardholder's account with the wallet provider. |
| `reason_codes` | string[] | No | The reasons for suggested tokenization given by the card network. |
| `suggested_decision` | enum: approve, decline, require_auth | No | The recommendation on responding to the tokenization request. |
| `suggested_decision_version` | string | No | The version of the standard for mapping reason codes followed by the wallet provider. |


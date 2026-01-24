# issuing_network_token_network_data

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `device` | [issuing_network_token_device](issuing-network-token-device.md) | No |  |
| `mastercard` | [issuing_network_token_mastercard](issuing-network-token-mastercard.md) | No |  |
| `type` | enum: mastercard, visa | Yes | The network that the token is associated with. An additional hash is included with a name matching this value, containing tokenization data specific to the card network. |
| `visa` | [issuing_network_token_visa](issuing-network-token-visa.md) | No |  |
| `wallet_provider` | [issuing_network_token_wallet_provider](issuing-network-token-wallet-provider.md) | No |  |


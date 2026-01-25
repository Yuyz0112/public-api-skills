# payment_method_details_crypto

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `buyer_address` | string | No | The wallet address of the customer. |
| `network` | enum: base, ethereum, polygon... | No | The blockchain network that the transaction was sent on. |
| `token_currency` | enum: usdc, usdg, usdp | No | The token currency that the transaction was sent with. |
| `transaction_hash` | string | No | The blockchain transaction hash of the crypto payment. |


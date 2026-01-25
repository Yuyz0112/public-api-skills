# balance_amount_net

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount` | integer | Yes | Balance amount. |
| `currency` | string (currency) | Yes | Three-letter [ISO currency code](https://www.iso.org/iso-4217-currency-codes.html), in lowercase. Must be a [supported currency](https://stripe.com/docs/currencies). |
| `net_available` | balance_net_available[] | No | Breakdown of balance by destination. |
| `source_types` | [balance_amount_by_source_type](balance-amount-by-source-type.md) | No |  |


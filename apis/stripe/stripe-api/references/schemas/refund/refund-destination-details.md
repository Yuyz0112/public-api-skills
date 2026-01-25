# refund_destination_details

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `affirm` | [destination_details_unimplemented](destination-details-unimplemented.md) | No |  |
| `afterpay_clearpay` | [destination_details_unimplemented](destination-details-unimplemented.md) | No |  |
| `alipay` | [destination_details_unimplemented](destination-details-unimplemented.md) | No |  |
| `alma` | [destination_details_unimplemented](destination-details-unimplemented.md) | No |  |
| `amazon_pay` | [destination_details_unimplemented](destination-details-unimplemented.md) | No |  |
| `au_bank_transfer` | [destination_details_unimplemented](destination-details-unimplemented.md) | No |  |
| `blik` | [refund_destination_details_blik](refund-destination-details-blik.md) | No |  |
| `br_bank_transfer` | [refund_destination_details_br_bank_transfer](refund-destination-details-br-bank-transfer.md) | No |  |
| `card` | [refund_destination_details_card](refund-destination-details-card.md) | No |  |
| `cashapp` | [destination_details_unimplemented](destination-details-unimplemented.md) | No |  |
| `crypto` | [refund_destination_details_crypto](refund-destination-details-crypto.md) | No |  |
| `customer_cash_balance` | [destination_details_unimplemented](destination-details-unimplemented.md) | No |  |
| `eps` | [destination_details_unimplemented](destination-details-unimplemented.md) | No |  |
| `eu_bank_transfer` | [refund_destination_details_eu_bank_transfer](refund-destination-details-eu-bank-transfer.md) | No |  |
| `gb_bank_transfer` | [refund_destination_details_gb_bank_transfer](refund-destination-details-gb-bank-transfer.md) | No |  |
| `giropay` | [destination_details_unimplemented](destination-details-unimplemented.md) | No |  |
| `grabpay` | [destination_details_unimplemented](destination-details-unimplemented.md) | No |  |
| `jp_bank_transfer` | [refund_destination_details_jp_bank_transfer](refund-destination-details-jp-bank-transfer.md) | No |  |
| `klarna` | [destination_details_unimplemented](destination-details-unimplemented.md) | No |  |
| `mb_way` | [refund_destination_details_mb_way](refund-destination-details-mb-way.md) | No |  |
| `multibanco` | [refund_destination_details_multibanco](refund-destination-details-multibanco.md) | No |  |
| `mx_bank_transfer` | [refund_destination_details_mx_bank_transfer](refund-destination-details-mx-bank-transfer.md) | No |  |
| `nz_bank_transfer` | [destination_details_unimplemented](destination-details-unimplemented.md) | No |  |
| `p24` | [refund_destination_details_p24](refund-destination-details-p24.md) | No |  |
| `paynow` | [destination_details_unimplemented](destination-details-unimplemented.md) | No |  |
| `paypal` | [refund_destination_details_paypal](refund-destination-details-paypal.md) | No |  |
| `pix` | [destination_details_unimplemented](destination-details-unimplemented.md) | No |  |
| `revolut` | [destination_details_unimplemented](destination-details-unimplemented.md) | No |  |
| `sofort` | [destination_details_unimplemented](destination-details-unimplemented.md) | No |  |
| `swish` | [refund_destination_details_swish](refund-destination-details-swish.md) | No |  |
| `th_bank_transfer` | [refund_destination_details_th_bank_transfer](refund-destination-details-th-bank-transfer.md) | No |  |
| `twint` | [destination_details_unimplemented](destination-details-unimplemented.md) | No |  |
| `type` | string | Yes | The type of transaction-specific details of the payment method used in the refund (e.g., `card`). An additional hash is included on `destination_details` with a name matching this value. It contains information specific to the refund transaction. |
| `us_bank_transfer` | [refund_destination_details_us_bank_transfer](refund-destination-details-us-bank-transfer.md) | No |  |
| `wechat_pay` | [destination_details_unimplemented](destination-details-unimplemented.md) | No |  |
| `zip` | [destination_details_unimplemented](destination-details-unimplemented.md) | No |  |


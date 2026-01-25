# payment_method_details_passthrough_card

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `brand` | string | No | Card brand. Can be `amex`, `cartes_bancaires`, `diners`, `discover`, `eftpos_au`, `jcb`, `link`, `mastercard`, `unionpay`, `visa` or `unknown`. |
| `country` | string | No | Two-letter ISO code representing the country of the card. You could use this attribute to get a sense of the international breakdown of cards you've collected. |
| `exp_month` | integer | No | Two-digit number representing the card's expiration month. |
| `exp_year` | integer | No | Four-digit number representing the card's expiration year. |
| `funding` | string | No | Card funding type. Can be `credit`, `debit`, `prepaid`, or `unknown`. |
| `last4` | string | No | The last four digits of the card. |


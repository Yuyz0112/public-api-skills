# payment_method_card

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `brand` | string | Yes | Card brand. Can be `amex`, `cartes_bancaires`, `diners`, `discover`, `eftpos_au`, `jcb`, `link`, `mastercard`, `unionpay`, `visa` or `unknown`. |
| `checks` | any | No | Checks on Card address and CVC if provided. |
| `country` | string | No | Two-letter ISO code representing the country of the card. You could use this attribute to get a sense of the international breakdown of cards you've collected. |
| `display_brand` | string | No | The brand to use when displaying the card, this accounts for customer's brand choice on dual-branded cards. Can be `american_express`, `cartes_bancaires`, `diners_club`, `discover`, `eftpos_australia`, `interac`, `jcb`, `mastercard`, `union_pay`, `visa`, or `other` and may contain more values in the future. |
| `exp_month` | integer | Yes | Two-digit number representing the card's expiration month. |
| `exp_year` | integer | Yes | Four-digit number representing the card's expiration year. |
| `fingerprint` | string | No | Uniquely identifies this particular card number. You can use this attribute to check whether two customers who’ve signed up with you are using the same card number, for example. For payment methods that tokenize card information (Apple Pay, Google Pay), the tokenized number might be provided instead of the underlying card number.

*As of May 1, 2021, card fingerprint in India for Connect changed to allow two fingerprints for the same card---one for India and one for the rest of the world.* |
| `funding` | string | Yes | Card funding type. Can be `credit`, `debit`, `prepaid`, or `unknown`. |
| `generated_from` | any | No | Details of the original PaymentMethod that created this object. |
| `last4` | string | Yes | The last four digits of the card. |
| `networks` | any | No | Contains information about card networks that can be used to process the payment. |
| `regulated_status` | enum: regulated, unregulated | No | Status of a card based on the card issuer. |
| `three_d_secure_usage` | any | No | Contains details on how this Card may be used for 3D Secure authentication. |
| `wallet` | any | No | If this Card is part of a card wallet, this contains the details of the card wallet. |


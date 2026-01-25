# payment_method_details_interac_present

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `brand` | string | No | Card brand. Can be `interac`, `mastercard` or `visa`. |
| `cardholder_name` | string | No | The cardholder name as read from the card, in [ISO 7813](https://en.wikipedia.org/wiki/ISO/IEC_7813) format. May include alphanumeric characters, special characters and first/last name separator (`/`). In some cases, the cardholder name may not be available depending on how the issuer has configured the card. Cardholder name is typically not available on swipe or contactless payments, such as those made with Apple Pay and Google Pay. |
| `country` | string | No | Two-letter ISO code representing the country of the card. You could use this attribute to get a sense of the international breakdown of cards you've collected. |
| `description` | string | No | A high-level description of the type of cards issued in this range. |
| `emv_auth_data` | string | No | Authorization response cryptogram. |
| `exp_month` | integer | Yes | Two-digit number representing the card's expiration month. |
| `exp_year` | integer | Yes | Four-digit number representing the card's expiration year. |
| `fingerprint` | string | No | Uniquely identifies this particular card number. You can use this attribute to check whether two customers who’ve signed up with you are using the same card number, for example. For payment methods that tokenize card information (Apple Pay, Google Pay), the tokenized number might be provided instead of the underlying card number.

*As of May 1, 2021, card fingerprint in India for Connect changed to allow two fingerprints for the same card---one for India and one for the rest of the world.* |
| `funding` | string | No | Card funding type. Can be `credit`, `debit`, `prepaid`, or `unknown`. |
| `generated_card` | string | No | ID of a card PaymentMethod generated from the card_present PaymentMethod that may be attached to a Customer for future transactions. Only present if it was possible to generate a card PaymentMethod. |
| `issuer` | string | No | The name of the card's issuing bank. |
| `last4` | string | No | The last four digits of the card. |
| `network` | string | No | Identifies which network this charge was processed on. Can be `amex`, `cartes_bancaires`, `diners`, `discover`, `eftpos_au`, `interac`, `jcb`, `link`, `mastercard`, `unionpay`, `visa`, or `unknown`. |
| `network_transaction_id` | string | No | This is used by the financial networks to identify a transaction. Visa calls this the Transaction ID, Mastercard calls this the Trace ID, and American Express calls this the Acquirer Reference Data. This value will be present if it is returned by the financial network in the authorization response, and null otherwise. |
| `preferred_locales` | string[] | No | The languages that the issuing bank recommends using for localizing any customer-facing text, as read from the card. Referenced from EMV tag 5F2D, data encoded on the card's chip. |
| `read_method` | enum: contact_emv, contactless_emv, contactless_magstripe_mode... | No | How card details were read in this transaction. |
| `receipt` | any | No | A collection of fields required to be displayed on receipts. Only required for EMV transactions. |


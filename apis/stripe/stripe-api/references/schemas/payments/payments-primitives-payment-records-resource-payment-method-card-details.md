# payments_primitives_payment_records_resource_payment_method_card_details

Details of the card used for this payment attempt.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `authorization_code` | string | No | The authorization code of the payment. |
| `brand` | enum: amex, cartes_bancaires, diners... | Yes | Card brand. Can be `amex`, `cartes_bancaires`, `diners`, `discover`, `eftpos_au`, `jcb`, `link`, `mastercard`, `unionpay`, `visa` or `unknown`. |
| `capture_before` | integer (unix-time) | No | When using manual capture, a future timestamp at which the charge will be automatically refunded if uncaptured. |
| `checks` | any | No | Check results by Card networks on Card address and CVC at time of payment. |
| `country` | string | No | Two-letter ISO code representing the country of the card. You could use this attribute to get a sense of the international breakdown of cards you've collected. |
| `description` | string | No | A high-level description of the type of cards issued in this range. |
| `exp_month` | integer | Yes | Two-digit number representing the card's expiration month. |
| `exp_year` | integer | Yes | Four-digit number representing the card's expiration year. |
| `fingerprint` | string | No | Uniquely identifies this particular card number. You can use this attribute to check whether two customers who’ve signed up with you are using the same card number, for example. For payment methods that tokenize card information (Apple Pay, Google Pay), the tokenized number might be provided instead of the underlying card number.

*As of May 1, 2021, card fingerprint in India for Connect changed to allow two fingerprints for the same card---one for India and one for the rest of the world.* |
| `funding` | enum: credit, debit, prepaid... | Yes | Card funding type. Can be `credit`, `debit`, `prepaid`, or `unknown`. |
| `iin` | string | No | Issuer identification number of the card. |
| `installments` | any | No | Installment details for this payment. |
| `issuer` | string | No | The name of the card's issuing bank. |
| `last4` | string | Yes | The last four digits of the card. |
| `network` | enum: amex, cartes_bancaires, diners... | No | Identifies which network this charge was processed on. Can be `amex`, `cartes_bancaires`, `diners`, `discover`, `eftpos_au`, `interac`, `jcb`, `link`, `mastercard`, `unionpay`, `visa`, or `unknown`. |
| `network_advice_code` | string | No | Advice code from the card network for the failed payment. |
| `network_decline_code` | string | No | Decline code from the card network for the failed payment. |
| `network_token` | any | No | If this card has network token credentials, this contains the details of the network token credentials. |
| `network_transaction_id` | string | No | This is used by the financial networks to identify a transaction. Visa calls this the Transaction ID, Mastercard calls this the Trace ID, and American Express calls this the Acquirer Reference Data. This value will be present if it is returned by the financial network in the authorization response, and null otherwise. |
| `stored_credential_usage` | enum: recurring, unscheduled | No | The transaction type that was passed for an off-session, Merchant-Initiated transaction, one of `recurring` or `unscheduled`. |
| `three_d_secure` | any | No | Populated if this transaction used 3D Secure authentication. |
| `wallet` | any | No | If this Card is part of a card wallet, this contains the details of the card wallet. |


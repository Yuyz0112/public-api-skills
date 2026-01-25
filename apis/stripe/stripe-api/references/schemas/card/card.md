# card

You can store multiple cards on a customer in order to charge the customer
later. You can also store multiple debit cards on a recipient in order to
transfer to those cards later.

Related guide: [Card payments with Sources](https://docs.stripe.com/sources/cards)

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account` | any | No |  |
| `address_city` | string | No | City/District/Suburb/Town/Village. |
| `address_country` | string | No | Billing address country, if provided when creating card. |
| `address_line1` | string | No | Address line 1 (Street address/PO Box/Company name). |
| `address_line1_check` | string | No | If `address_line1` was provided, results of the check: `pass`, `fail`, `unavailable`, or `unchecked`. |
| `address_line2` | string | No | Address line 2 (Apartment/Suite/Unit/Building). |
| `address_state` | string | No | State/County/Province/Region. |
| `address_zip` | string | No | ZIP or postal code. |
| `address_zip_check` | string | No | If `address_zip` was provided, results of the check: `pass`, `fail`, `unavailable`, or `unchecked`. |
| `allow_redisplay` | enum: always, limited, unspecified | No | This field indicates whether this payment method can be shown again to its customer in a checkout flow. Stripe products such as Checkout and Elements use this field to determine whether a payment method can be shown as a saved payment method in a checkout flow. The field defaults to “unspecified”. |
| `available_payout_methods` | string[] | No | A set of available payout methods for this card. Only values from this set should be passed as the `method` when creating a payout. |
| `brand` | string | Yes | Card brand. Can be `American Express`, `Cartes Bancaires`, `Diners Club`, `Discover`, `Eftpos Australia`, `Girocard`, `JCB`, `MasterCard`, `UnionPay`, `Visa`, or `Unknown`. |
| `country` | string | No | Two-letter ISO code representing the country of the card. You could use this attribute to get a sense of the international breakdown of cards you've collected. |
| `currency` | string (currency) | No | Three-letter [ISO code for currency](https://www.iso.org/iso-4217-currency-codes.html) in lowercase. Must be a [supported currency](https://docs.stripe.com/currencies). Only applicable on accounts (not customers or recipients). The card can be used as a transfer destination for funds in this currency. This property is only available when returned as an [External Account](/api/external_account_cards/object) where [controller.is_controller](/api/accounts/object#account_object-controller-is_controller) is `true`. |
| `customer` | any | No | The customer that this card belongs to. This attribute will not be in the card object if the card belongs to an account or recipient instead. |
| `cvc_check` | string | No | If a CVC was provided, results of the check: `pass`, `fail`, `unavailable`, or `unchecked`. A result of unchecked indicates that CVC was provided but hasn't been checked yet. Checks are typically performed when attaching a card to a Customer object, or when creating a charge. For more details, see [Check if a card is valid without a charge](https://support.stripe.com/questions/check-if-a-card-is-valid-without-a-charge). |
| `default_for_currency` | boolean | No | Whether this card is the default external account for its currency. This property is only available for accounts where [controller.requirement_collection](/api/accounts/object#account_object-controller-requirement_collection) is `application`, which includes Custom accounts. |
| `dynamic_last4` | string | No | (For tokenized numbers only.) The last four digits of the device account number. |
| `exp_month` | integer | Yes | Two-digit number representing the card's expiration month. |
| `exp_year` | integer | Yes | Four-digit number representing the card's expiration year. |
| `fingerprint` | string | No | Uniquely identifies this particular card number. You can use this attribute to check whether two customers who’ve signed up with you are using the same card number, for example. For payment methods that tokenize card information (Apple Pay, Google Pay), the tokenized number might be provided instead of the underlying card number.

*As of May 1, 2021, card fingerprint in India for Connect changed to allow two fingerprints for the same card---one for India and one for the rest of the world.* |
| `funding` | string | Yes | Card funding type. Can be `credit`, `debit`, `prepaid`, or `unknown`. |
| `id` | string | Yes | Unique identifier for the object. |
| `iin` | string | No | Issuer identification number of the card. |
| `last4` | string | Yes | The last four digits of the card. |
| `metadata` | object | No | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `name` | string | No | Cardholder name. |
| `networks` | [token_card_networks](token-card-networks.md) | No |  |
| `object` | enum: card | Yes | String representing the object's type. Objects of the same type share the same value. |
| `regulated_status` | enum: regulated, unregulated | No | Status of a card based on the card issuer. |
| `status` | string | No | For external accounts that are cards, possible values are `new` and `errored`. If a payout fails, the status is set to `errored` and [scheduled payouts](https://stripe.com/docs/payouts#payout-schedule) are stopped until account details are updated. |
| `tokenization_method` | string | No | If the card number is tokenized, this is the method that was used. Can be `android_pay` (includes Google Pay), `apple_pay`, `masterpass`, `visa_checkout`, or null. |


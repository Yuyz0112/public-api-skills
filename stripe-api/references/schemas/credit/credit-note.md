# credit_note

Issue a credit note to adjust an invoice's amount after the invoice is finalized.

Related guide: [Credit notes](https://docs.stripe.com/billing/invoices/credit-notes)

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount` | integer | Yes | The integer amount in cents (or local equivalent) representing the total amount of the credit note, including tax. |
| `amount_shipping` | integer | Yes | This is the sum of all the shipping amounts. |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `currency` | string (currency) | Yes | Three-letter [ISO currency code](https://www.iso.org/iso-4217-currency-codes.html), in lowercase. Must be a [supported currency](https://stripe.com/docs/currencies). |
| `customer` | any | Yes | ID of the customer. |
| `customer_account` | string | No | ID of the account representing the customer. |
| `customer_balance_transaction` | any | No | Customer balance transaction related to this credit note. |
| `discount_amount` | integer | Yes | The integer amount in cents (or local equivalent) representing the total amount of discount that was credited. |
| `discount_amounts` | discounts_resource_discount_amount[] | Yes | The aggregate amounts calculated per discount for all line items. |
| `effective_at` | integer (unix-time) | No | The date when this credit note is in effect. Same as `created` unless overwritten. When defined, this value replaces the system-generated 'Date of issue' printed on the credit note PDF. |
| `id` | string | Yes | Unique identifier for the object. |
| `invoice` | any | Yes | ID of the invoice. |
| `lines` | object | Yes | Line items that make up the credit note |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `memo` | string | No | Customer-facing text that appears on the credit note PDF. |
| `metadata` | object | No | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `number` | string | Yes | A unique number that identifies this particular credit note and appears on the PDF of the credit note and its associated invoice. |
| `object` | enum: credit_note | Yes | String representing the object's type. Objects of the same type share the same value. |
| `out_of_band_amount` | integer | No | Amount that was credited outside of Stripe. |
| `pdf` | string | Yes | The link to download the PDF of the credit note. |
| `post_payment_amount` | integer | Yes | The amount of the credit note that was refunded to the customer, credited to the customer's balance, credited outside of Stripe, or any combination thereof. |
| `pre_payment_amount` | integer | Yes | The amount of the credit note by which the invoice's `amount_remaining` and `amount_due` were reduced. |
| `pretax_credit_amounts` | credit_notes_pretax_credit_amount[] | Yes | The pretax credit amounts (ex: discount, credit grants, etc) for all line items. |
| `reason` | enum: duplicate, fraudulent, order_change... | No | Reason for issuing this credit note, one of `duplicate`, `fraudulent`, `order_change`, or `product_unsatisfactory` |
| `refunds` | credit_note_refund[] | Yes | Refunds related to this credit note. |
| `shipping_cost` | any | No | The details of the cost of shipping, including the ShippingRate applied to the invoice. |
| `status` | enum: issued, void | Yes | Status of this credit note, one of `issued` or `void`. Learn more about [voiding credit notes](https://docs.stripe.com/billing/invoices/credit-notes#voiding). |
| `subtotal` | integer | Yes | The integer amount in cents (or local equivalent) representing the amount of the credit note, excluding exclusive tax and invoice level discounts. |
| `subtotal_excluding_tax` | integer | No | The integer amount in cents (or local equivalent) representing the amount of the credit note, excluding all tax and invoice level discounts. |
| `total` | integer | Yes | The integer amount in cents (or local equivalent) representing the total amount of the credit note, including tax and all discount. |
| `total_excluding_tax` | integer | No | The integer amount in cents (or local equivalent) representing the total amount of the credit note, excluding tax, but including discounts. |
| `total_taxes` | billing_bill_resource_invoicing_taxes_tax[] | No | The aggregate tax information for all line items. |
| `type` | enum: mixed, post_payment, pre_payment | Yes | Type of this credit note, one of `pre_payment` or `post_payment`. A `pre_payment` credit note means it was issued when the invoice was open. A `post_payment` credit note means it was issued when the invoice was paid. |
| `voided_at` | integer (unix-time) | No | The time that the credit note was voided. |

## Nested Fields

### `lines`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | credit_note_line_item[] | Yes | Details about each object. |
| `has_more` | boolean | Yes | True if this list has another page of items after this one that can be fetched. |
| `object` | enum: list | Yes | String representing the object's type. Objects of the same type share the same value. Always has the value `list`. |
| `url` | string | Yes | The URL where this list can be accessed. |


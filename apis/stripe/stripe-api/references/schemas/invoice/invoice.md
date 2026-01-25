# invoice

Invoices are statements of amounts owed by a customer, and are either
generated one-off, or generated periodically from a subscription.

They contain [invoice items](https://api.stripe.com#invoiceitems), and proration adjustments
that may be caused by subscription upgrades/downgrades (if necessary).

If your invoice is configured to be billed through automatic charges,
Stripe automatically finalizes your invoice and attempts payment. Note
that finalizing the invoice,
[when automatic](https://docs.stripe.com/invoicing/integration/automatic-advancement-collection), does
not happen immediately as the invoice is created. Stripe waits
until one hour after the last webhook was successfully sent (or the last
webhook timed out after failing). If you (and the platforms you may have
connected to) have no webhooks configured, Stripe waits one hour after
creation to finalize the invoice.

If your invoice is configured to be billed by sending an email, then based on your
[email settings](https://dashboard.stripe.com/account/billing/automatic),
Stripe will email the invoice to your customer and await payment. These
emails can contain a link to a hosted page to pay the invoice.

Stripe applies any customer credit on the account before determining the
amount due for the invoice (i.e., the amount that will be actually
charged). If the amount due for the invoice is less than Stripe's [minimum allowed charge
per currency](/docs/currencies#minimum-and-maximum-charge-amounts), the
invoice is automatically marked paid, and we add the amount due to the
customer's credit balance which is applied to the next invoice.

More details on the customer's credit balance are
[here](https://docs.stripe.com/billing/customer/balance).

Related guide: [Send invoices to customers](https://docs.stripe.com/billing/invoices/sending)

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account_country` | string | No | The country of the business associated with this invoice, most often the business creating the invoice. |
| `account_name` | string | No | The public name of the business associated with this invoice, most often the business creating the invoice. |
| `account_tax_ids` | any[] | No | The account tax IDs associated with the invoice. Only editable when the invoice is a draft. |
| `amount_due` | integer | Yes | Final amount due at this time for this invoice. If the invoice's total is smaller than the minimum charge amount, for example, or if there is account credit that can be applied to the invoice, the `amount_due` may be 0. If there is a positive `starting_balance` for the invoice (the customer owes money), the `amount_due` will also take that into account. The charge that gets generated for the invoice will be for the amount specified in `amount_due`. |
| `amount_overpaid` | integer | Yes | Amount that was overpaid on the invoice. The amount overpaid is credited to the customer's credit balance. |
| `amount_paid` | integer | Yes | The amount, in cents (or local equivalent), that was paid. |
| `amount_remaining` | integer | Yes | The difference between amount_due and amount_paid, in cents (or local equivalent). |
| `amount_shipping` | integer | Yes | This is the sum of all the shipping amounts. |
| `application` | any | No | ID of the Connect Application that created the invoice. |
| `attempt_count` | integer | Yes | Number of payment attempts made for this invoice, from the perspective of the payment retry schedule. Any payment attempt counts as the first attempt, and subsequently only automatic retries increment the attempt count. In other words, manual payment attempts after the first attempt do not affect the retry schedule. If a failure is returned with a non-retryable return code, the invoice can no longer be retried unless a new payment method is obtained. Retries will continue to be scheduled, and attempt_count will continue to increment, but retries will only be executed if a new payment method is obtained. |
| `attempted` | boolean | Yes | Whether an attempt has been made to pay the invoice. An invoice is not attempted until 1 hour after the `invoice.created` webhook, for example, so you might not want to display that invoice as unpaid to your users. |
| `auto_advance` | boolean | Yes | Controls whether Stripe performs [automatic collection](https://docs.stripe.com/invoicing/integration/automatic-advancement-collection) of the invoice. If `false`, the invoice's state doesn't automatically advance without an explicit action. |
| `automatic_tax` | [automatic_tax](automatic-tax.md) | Yes |  |
| `automatically_finalizes_at` | integer (unix-time) | No | The time when this invoice is currently scheduled to be automatically finalized. The field will be `null` if the invoice is not scheduled to finalize in the future. If the invoice is not in the draft state, this field will always be `null` - see `finalized_at` for the time when an already-finalized invoice was finalized. |
| `billing_reason` | enum: automatic_pending_invoice_item_invoice, manual, quote_accept... | No | Indicates the reason why the invoice was created.

* `manual`: Unrelated to a subscription, for example, created via the invoice editor.
* `subscription`: No longer in use. Applies to subscriptions from before May 2018 where no distinction was made between updates, cycles, and thresholds.
* `subscription_create`: A new subscription was created.
* `subscription_cycle`: A subscription advanced into a new period.
* `subscription_threshold`: A subscription reached a billing threshold.
* `subscription_update`: A subscription was updated.
* `upcoming`: Reserved for upcoming invoices created through the Create Preview Invoice API or when an `invoice.upcoming` event is generated for an upcoming invoice on a subscription. |
| `collection_method` | enum: charge_automatically, send_invoice | Yes | Either `charge_automatically`, or `send_invoice`. When charging automatically, Stripe will attempt to pay this invoice using the default source attached to the customer. When sending an invoice, Stripe will email this invoice to the customer with payment instructions. |
| `confirmation_secret` | any | No | The confirmation secret associated with this invoice. Currently, this contains the client_secret of the PaymentIntent that Stripe creates during invoice finalization. |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `currency` | string (currency) | Yes | Three-letter [ISO currency code](https://www.iso.org/iso-4217-currency-codes.html), in lowercase. Must be a [supported currency](https://stripe.com/docs/currencies). |
| `custom_fields` | invoice_setting_custom_field[] | No | Custom fields displayed on the invoice. |
| `customer` | any | Yes | The ID of the customer to bill. |
| `customer_account` | string | No | The ID of the account representing the customer to bill. |
| `customer_address` | any | No | The customer's address. Until the invoice is finalized, this field will equal `customer.address`. Once the invoice is finalized, this field will no longer be updated. |
| `customer_email` | string | No | The customer's email. Until the invoice is finalized, this field will equal `customer.email`. Once the invoice is finalized, this field will no longer be updated. |
| `customer_name` | string | No | The customer's name. Until the invoice is finalized, this field will equal `customer.name`. Once the invoice is finalized, this field will no longer be updated. |
| `customer_phone` | string | No | The customer's phone number. Until the invoice is finalized, this field will equal `customer.phone`. Once the invoice is finalized, this field will no longer be updated. |
| `customer_shipping` | any | No | The customer's shipping information. Until the invoice is finalized, this field will equal `customer.shipping`. Once the invoice is finalized, this field will no longer be updated. |
| `customer_tax_exempt` | enum: exempt, none, reverse | No | The customer's tax exempt status. Until the invoice is finalized, this field will equal `customer.tax_exempt`. Once the invoice is finalized, this field will no longer be updated. |
| `customer_tax_ids` | invoices_resource_invoice_tax_id[] | No | The customer's tax IDs. Until the invoice is finalized, this field will contain the same tax IDs as `customer.tax_ids`. Once the invoice is finalized, this field will no longer be updated. |
| `default_payment_method` | any | No | ID of the default payment method for the invoice. It must belong to the customer associated with the invoice. If not set, defaults to the subscription's default payment method, if any, or to the default payment method in the customer's invoice settings. |
| `default_source` | any | No | ID of the default payment source for the invoice. It must belong to the customer associated with the invoice and be in a chargeable state. If not set, defaults to the subscription's default source, if any, or to the customer's default source. |
| `default_tax_rates` | tax_rate[] | Yes | The tax rates applied to this invoice, if any. |
| `description` | string | No | An arbitrary string attached to the object. Often useful for displaying to users. Referenced as 'memo' in the Dashboard. |
| `discounts` | any[] | Yes | The discounts applied to the invoice. Line item discounts are applied before invoice discounts. Use `expand[]=discounts` to expand each discount. |
| `due_date` | integer (unix-time) | No | The date on which payment for this invoice is due. This value will be `null` for invoices where `collection_method=charge_automatically`. |
| `effective_at` | integer (unix-time) | No | The date when this invoice is in effect. Same as `finalized_at` unless overwritten. When defined, this value replaces the system-generated 'Date of issue' printed on the invoice PDF and receipt. |
| `ending_balance` | integer | No | Ending customer balance after the invoice is finalized. Invoices are finalized approximately an hour after successful webhook delivery or when payment collection is attempted for the invoice. If the invoice has not been finalized yet, this will be null. |
| `footer` | string | No | Footer displayed on the invoice. |
| `from_invoice` | any | No | Details of the invoice that was cloned. See the [revision documentation](https://docs.stripe.com/invoicing/invoice-revisions) for more details. |
| `hosted_invoice_url` | string | No | The URL for the hosted invoice page, which allows customers to view and pay an invoice. If the invoice has not been finalized yet, this will be null. |
| `id` | string | Yes | Unique identifier for the object. For preview invoices created using the [create preview](https://stripe.com/docs/api/invoices/create_preview) endpoint, this id will be prefixed with `upcoming_in`. |
| `invoice_pdf` | string | No | The link to download the PDF for the invoice. If the invoice has not been finalized yet, this will be null. |
| `issuer` | [connect_account_reference](connect-account-reference.md) | Yes |  |
| `last_finalization_error` | any | No | The error encountered during the previous attempt to finalize the invoice. This field is cleared when the invoice is successfully finalized. |
| `latest_revision` | any | No | The ID of the most recent non-draft revision of this invoice |
| `lines` | object | Yes | The individual line items that make up the invoice. `lines` is sorted as follows: (1) pending invoice items (including prorations) in reverse chronological order, (2) subscription items in reverse chronological order, and (3) invoice items added after invoice creation in chronological order. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `metadata` | object | No | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `next_payment_attempt` | integer (unix-time) | No | The time at which payment will next be attempted. This value will be `null` for invoices where `collection_method=send_invoice`. |
| `number` | string | No | A unique, identifying string that appears on emails sent to the customer for this invoice. This starts with the customer's unique invoice_prefix if it is specified. |
| `object` | enum: invoice | Yes | String representing the object's type. Objects of the same type share the same value. |
| `on_behalf_of` | any | No | The account (if any) for which the funds of the invoice payment are intended. If set, the invoice will be presented with the branding and support information of the specified account. See the [Invoices with Connect](https://docs.stripe.com/billing/invoices/connect) documentation for details. |
| `parent` | any | No | The parent that generated this invoice |
| `payment_settings` | [invoices_payment_settings](invoices-payment-settings.md) | Yes |  |
| `payments` | object | No | Payments for this invoice |
| `period_end` | integer (unix-time) | Yes | End of the usage period during which invoice items were added to this invoice. This looks back one period for a subscription invoice. Use the [line item period](/api/invoices/line_item#invoice_line_item_object-period) to get the service period for each price. |
| `period_start` | integer (unix-time) | Yes | Start of the usage period during which invoice items were added to this invoice. This looks back one period for a subscription invoice. Use the [line item period](/api/invoices/line_item#invoice_line_item_object-period) to get the service period for each price. |
| `post_payment_credit_notes_amount` | integer | Yes | Total amount of all post-payment credit notes issued for this invoice. |
| `pre_payment_credit_notes_amount` | integer | Yes | Total amount of all pre-payment credit notes issued for this invoice. |
| `receipt_number` | string | No | This is the transaction number that appears on email receipts sent for this invoice. |
| `rendering` | any | No | The rendering-related settings that control how the invoice is displayed on customer-facing surfaces such as PDF and Hosted Invoice Page. |
| `shipping_cost` | any | No | The details of the cost of shipping, including the ShippingRate applied on the invoice. |
| `shipping_details` | any | No | Shipping details for the invoice. The Invoice PDF will use the `shipping_details` value if it is set, otherwise the PDF will render the shipping address from the customer. |
| `starting_balance` | integer | Yes | Starting customer balance before the invoice is finalized. If the invoice has not been finalized yet, this will be the current customer balance. For revision invoices, this also includes any customer balance that was applied to the original invoice. |
| `statement_descriptor` | string | No | Extra information about an invoice for the customer's credit card statement. |
| `status` | enum: draft, open, paid... | No | The status of the invoice, one of `draft`, `open`, `paid`, `uncollectible`, or `void`. [Learn more](https://docs.stripe.com/billing/invoices/workflow#workflow-overview) |
| `status_transitions` | [invoices_resource_status_transitions](invoices-resource-status-transitions.md) | Yes |  |
| `subtotal` | integer | Yes | Total of all subscriptions, invoice items, and prorations on the invoice before any invoice level discount or exclusive tax is applied. Item discounts are already incorporated |
| `subtotal_excluding_tax` | integer | No | The integer amount in cents (or local equivalent) representing the subtotal of the invoice before any invoice level discount or tax is applied. Item discounts are already incorporated |
| `test_clock` | any | No | ID of the test clock this invoice belongs to. |
| `threshold_reason` | [invoice_threshold_reason](invoice-threshold-reason.md) | No |  |
| `total` | integer | Yes | Total after discounts and taxes. |
| `total_discount_amounts` | discounts_resource_discount_amount[] | No | The aggregate amounts calculated per discount across all line items. |
| `total_excluding_tax` | integer | No | The integer amount in cents (or local equivalent) representing the total amount of the invoice including all discounts but excluding all tax. |
| `total_pretax_credit_amounts` | invoices_resource_pretax_credit_amount[] | No | Contains pretax credit amounts (ex: discount, credit grants, etc) that apply to this invoice. This is a combined list of total_pretax_credit_amounts across all invoice line items. |
| `total_taxes` | billing_bill_resource_invoicing_taxes_tax[] | No | The aggregate tax information of all line items. |
| `webhooks_delivered_at` | integer (unix-time) | No | Invoices are automatically paid or sent 1 hour after webhooks are delivered, or until all webhook delivery attempts have [been exhausted](https://docs.stripe.com/billing/webhooks#understand). This field tracks the time when webhooks for this invoice were successfully delivered. If the invoice had no webhooks to deliver, this will be set while the invoice is being created. |

## Nested Fields

### `lines`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | line_item[] | Yes | Details about each object. |
| `has_more` | boolean | Yes | True if this list has another page of items after this one that can be fetched. |
| `object` | enum: list | Yes | String representing the object's type. Objects of the same type share the same value. Always has the value `list`. |
| `url` | string | Yes | The URL where this list can be accessed. |

### `payments`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | invoice_payment[] | Yes | Details about each object. |
| `has_more` | boolean | Yes | True if this list has another page of items after this one that can be fetched. |
| `object` | enum: list | Yes | String representing the object's type. Objects of the same type share the same value. Always has the value `list`. |
| `url` | string | Yes | The URL where this list can be accessed. |


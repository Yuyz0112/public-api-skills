# invoiceitem

Invoice Items represent the component lines of an [invoice](https://docs.stripe.com/api/invoices). When you create an invoice item with an `invoice` field, it is attached to the specified invoice and included as [an invoice line item](https://docs.stripe.com/api/invoices/line_item) within [invoice.lines](https://docs.stripe.com/api/invoices/object#invoice_object-lines).

Invoice Items can be created before you are ready to actually send the invoice. This can be particularly useful when combined
with a [subscription](https://docs.stripe.com/api/subscriptions). Sometimes you want to add a charge or credit to a customer, but actually charge
or credit the customer's card only at the end of a regular billing cycle. This is useful for combining several charges
(to minimize per-transaction fees), or for having Stripe tabulate your usage-based billing totals.

Related guides: [Integrate with the Invoicing API](https://docs.stripe.com/invoicing/integration), [Subscription Invoices](https://docs.stripe.com/billing/invoices/subscription#adding-upcoming-invoice-items).

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount` | integer | Yes | Amount (in the `currency` specified) of the invoice item. This should always be equal to `unit_amount * quantity`. |
| `currency` | string (currency) | Yes | Three-letter [ISO currency code](https://www.iso.org/iso-4217-currency-codes.html), in lowercase. Must be a [supported currency](https://stripe.com/docs/currencies). |
| `customer` | any | Yes | The ID of the customer to bill for this invoice item. |
| `customer_account` | string | No | The ID of the account to bill for this invoice item. |
| `date` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `description` | string | No | An arbitrary string attached to the object. Often useful for displaying to users. |
| `discountable` | boolean | Yes | If true, discounts will apply to this invoice item. Always false for prorations. |
| `discounts` | any[] | No | The discounts which apply to the invoice item. Item discounts are applied before invoice discounts. Use `expand[]=discounts` to expand each discount. |
| `id` | string | Yes | Unique identifier for the object. |
| `invoice` | any | No | The ID of the invoice this invoice item belongs to. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `metadata` | object | No | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `net_amount` | integer | No | The amount after discounts, but before credits and taxes. This field is `null` for `discountable=true` items. |
| `object` | enum: invoiceitem | Yes | String representing the object's type. Objects of the same type share the same value. |
| `parent` | any | No | The parent that generated this invoice item. |
| `period` | [invoice_line_item_period](invoice-line-item-period.md) | Yes |  |
| `pricing` | any | No | The pricing information of the invoice item. |
| `proration` | boolean | Yes | Whether the invoice item was created automatically as a proration adjustment when the customer switched plans. |
| `proration_details` | [proration_details](proration-details.md) | No |  |
| `quantity` | integer | Yes | Quantity of units for the invoice item. If the invoice item is a proration, the quantity of the subscription that the proration was computed for. |
| `tax_rates` | tax_rate[] | No | The tax rates which apply to the invoice item. When set, the `default_tax_rates` on the invoice do not apply to this invoice item. |
| `test_clock` | any | No | ID of the test clock this invoice item belongs to. |


# line_item

Invoice Line Items represent the individual lines within an [invoice](https://docs.stripe.com/api/invoices) and only exist within the context of an invoice.

Each line item is backed by either an [invoice item](https://docs.stripe.com/api/invoiceitems) or a [subscription item](https://docs.stripe.com/api/subscription_items).

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount` | integer | Yes | The amount, in cents (or local equivalent). |
| `currency` | string (currency) | Yes | Three-letter [ISO currency code](https://www.iso.org/iso-4217-currency-codes.html), in lowercase. Must be a [supported currency](https://stripe.com/docs/currencies). |
| `description` | string | No | An arbitrary string attached to the object. Often useful for displaying to users. |
| `discount_amounts` | discounts_resource_discount_amount[] | No | The amount of discount calculated per discount for this line item. |
| `discountable` | boolean | Yes | If true, discounts will apply to this line item. Always false for prorations. |
| `discounts` | any[] | Yes | The discounts applied to the invoice line item. Line item discounts are applied before invoice discounts. Use `expand[]=discounts` to expand each discount. |
| `id` | string | Yes | Unique identifier for the object. |
| `invoice` | string | No | The ID of the invoice that contains this line item. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `metadata` | object | Yes | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. Note that for line items with `type=subscription`, `metadata` reflects the current metadata from the subscription associated with the line item, unless the invoice line was directly updated with different metadata after creation. |
| `object` | enum: line_item | Yes | String representing the object's type. Objects of the same type share the same value. |
| `parent` | any | No | The parent that generated this line item. |
| `period` | [invoice_line_item_period](invoice-line-item-period.md) | Yes |  |
| `pretax_credit_amounts` | invoices_resource_pretax_credit_amount[] | No | Contains pretax credit amounts (ex: discount, credit grants, etc) that apply to this line item. |
| `pricing` | any | No | The pricing information of the line item. |
| `quantity` | integer | No | The quantity of the subscription, if the line item is a subscription or a proration. |
| `subscription` | any | No |  |
| `subtotal` | integer | Yes | The subtotal of the line item, in cents (or local equivalent), before any discounts or taxes. |
| `taxes` | billing_bill_resource_invoicing_taxes_tax[] | No | The tax information of the line item. |


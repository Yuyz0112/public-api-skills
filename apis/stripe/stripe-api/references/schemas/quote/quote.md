# quote

A Quote is a way to model prices that you'd like to provide to a customer.
Once accepted, it will automatically create an invoice, subscription or subscription schedule.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount_subtotal` | integer | Yes | Total before any discounts or taxes are applied. |
| `amount_total` | integer | Yes | Total after discounts and taxes are applied. |
| `application` | any | No | ID of the Connect Application that created the quote. |
| `application_fee_amount` | integer | No | The amount of the application fee (if any) that will be requested to be applied to the payment and transferred to the application owner's Stripe account. Only applicable if there are no line items with recurring prices on the quote. |
| `application_fee_percent` | number | No | A non-negative decimal between 0 and 100, with at most two decimal places. This represents the percentage of the subscription invoice total that will be transferred to the application owner's Stripe account. Only applicable if there are line items with recurring prices on the quote. |
| `automatic_tax` | [quotes_resource_automatic_tax](quotes-resource-automatic-tax.md) | Yes |  |
| `collection_method` | enum: charge_automatically, send_invoice | Yes | Either `charge_automatically`, or `send_invoice`. When charging automatically, Stripe will attempt to pay invoices at the end of the subscription cycle or on finalization using the default payment method attached to the subscription or customer. When sending an invoice, Stripe will email your customer an invoice with payment instructions and mark the subscription as `active`. Defaults to `charge_automatically`. |
| `computed` | [quotes_resource_computed](quotes-resource-computed.md) | Yes |  |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `currency` | string | No | Three-letter [ISO currency code](https://www.iso.org/iso-4217-currency-codes.html), in lowercase. Must be a [supported currency](https://stripe.com/docs/currencies). |
| `customer` | any | No | The customer who received this quote. A customer is required to finalize the quote. Once specified, you can't change it. |
| `customer_account` | string | No | The account representing the customer who received this quote. A customer or account is required to finalize the quote. Once specified, you can't change it. |
| `default_tax_rates` | any[] | No | The tax rates applied to this quote. |
| `description` | string | No | A description that will be displayed on the quote PDF. |
| `discounts` | any[] | Yes | The discounts applied to this quote. |
| `expires_at` | integer (unix-time) | Yes | The date on which the quote will be canceled if in `open` or `draft` status. Measured in seconds since the Unix epoch. |
| `footer` | string | No | A footer that will be displayed on the quote PDF. |
| `from_quote` | any | No | Details of the quote that was cloned. See the [cloning documentation](https://docs.stripe.com/quotes/clone) for more details. |
| `header` | string | No | A header that will be displayed on the quote PDF. |
| `id` | string | Yes | Unique identifier for the object. |
| `invoice` | any | No | The invoice that was created from this quote. |
| `invoice_settings` | [invoice_setting_quote_setting](invoice-setting-quote-setting.md) | Yes |  |
| `line_items` | object | No | A list of items the customer is being quoted for. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `metadata` | object | Yes | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `number` | string | No | A unique number that identifies this particular quote. This number is assigned once the quote is [finalized](https://docs.stripe.com/quotes/overview#finalize). |
| `object` | enum: quote | Yes | String representing the object's type. Objects of the same type share the same value. |
| `on_behalf_of` | any | No | The account on behalf of which to charge. See the [Connect documentation](https://support.stripe.com/questions/sending-invoices-on-behalf-of-connected-accounts) for details. |
| `status` | enum: accepted, canceled, draft... | Yes | The status of the quote. |
| `status_transitions` | [quotes_resource_status_transitions](quotes-resource-status-transitions.md) | Yes |  |
| `subscription` | any | No | The subscription that was created or updated from this quote. |
| `subscription_data` | [quotes_resource_subscription_data_subscription_data](quotes-resource-subscription-data-subscription-data.md) | Yes |  |
| `subscription_schedule` | any | No | The subscription schedule that was created or updated from this quote. |
| `test_clock` | any | No | ID of the test clock this quote belongs to. |
| `total_details` | [quotes_resource_total_details](quotes-resource-total-details.md) | Yes |  |
| `transfer_data` | any | No | The account (if any) the payments will be attributed to for tax reporting, and where funds from each payment will be transferred to for each of the invoices. |

## Nested Fields

### `line_items`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | item[] | Yes | Details about each object. |
| `has_more` | boolean | Yes | True if this list has another page of items after this one that can be fetched. |
| `object` | enum: list | Yes | String representing the object's type. Objects of the same type share the same value. Always has the value `list`. |
| `url` | string | Yes | The URL where this list can be accessed. |


# customer

This object represents a customer of your business. Use it to [create recurring charges](https://docs.stripe.com/invoicing/customer), [save payment](https://docs.stripe.com/payments/save-during-payment) and contact information,
and track payments that belong to the same customer.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `address` | any | No | The customer's address. |
| `balance` | integer | No | The current balance, if any, that's stored on the customer in their default currency. If negative, the customer has credit to apply to their next invoice. If positive, the customer has an amount owed that's added to their next invoice. The balance only considers amounts that Stripe hasn't successfully applied to any invoice. It doesn't reflect unpaid invoices. This balance is only taken into account after invoices finalize. For multi-currency balances, see [invoice_credit_balance](https://docs.stripe.com/api/customers/object#customer_object-invoice_credit_balance). |
| `business_name` | string | No | The customer's business name. |
| `cash_balance` | any | No | The current funds being held by Stripe on behalf of the customer. You can apply these funds towards payment intents when the source is "cash_balance". The `settings[reconciliation_mode]` field describes if these funds apply to these payment intents manually or automatically. |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `currency` | string | No | Three-letter [ISO code for the currency](https://stripe.com/docs/currencies) the customer can be charged in for recurring billing purposes. |
| `customer_account` | string | No | The ID of an Account representing a customer. You can use this ID with any v1 API that accepts a customer_account parameter. |
| `default_source` | any | No | ID of the default payment source for the customer.

If you use payment methods created through the PaymentMethods API, see the [invoice_settings.default_payment_method](https://docs.stripe.com/api/customers/object#customer_object-invoice_settings-default_payment_method) field instead. |
| `delinquent` | boolean | No | Tracks the most recent state change on any invoice belonging to the customer. Paying an invoice or marking it uncollectible via the API will set this field to false. An automatic payment failure or passing the `invoice.due_date` will set this field to `true`.

If an invoice becomes uncollectible by [dunning](https://docs.stripe.com/billing/automatic-collection), `delinquent` doesn't reset to `false`.

If you care whether the customer has paid their most recent subscription invoice, use `subscription.status` instead. Paying or marking uncollectible any customer invoice regardless of whether it is the latest invoice for a subscription will always set this field to `false`. |
| `description` | string | No | An arbitrary string attached to the object. Often useful for displaying to users. |
| `discount` | any | No | Describes the current discount active on the customer, if there is one. |
| `email` | string | No | The customer's email address. |
| `id` | string | Yes | Unique identifier for the object. |
| `individual_name` | string | No | The customer's individual name. |
| `invoice_credit_balance` | object | No | The current multi-currency balances, if any, that's stored on the customer. If positive in a currency, the customer has a credit to apply to their next invoice denominated in that currency. If negative, the customer has an amount owed that's added to their next invoice denominated in that currency. These balances don't apply to unpaid invoices. They solely track amounts that Stripe hasn't successfully applied to any invoice. Stripe only applies a balance in a specific currency to an invoice after that invoice (which is in the same currency) finalizes. |
| `invoice_prefix` | string | No | The prefix for the customer used to generate unique invoice numbers. |
| `invoice_settings` | [invoice_setting_customer_setting](invoice-setting-customer-setting.md) | No |  |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `metadata` | object | No | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `name` | string | No | The customer's full name or business name. |
| `next_invoice_sequence` | integer | No | The suffix of the customer's next invoice number (for example, 0001). When the account uses account level sequencing, this parameter is ignored in API requests and the field omitted in API responses. |
| `object` | enum: customer | Yes | String representing the object's type. Objects of the same type share the same value. |
| `phone` | string | No | The customer's phone number. |
| `preferred_locales` | string[] | No | The customer's preferred locales (languages), ordered by preference. |
| `shipping` | any | No | Mailing and shipping address for the customer. Appears on invoices emailed to this customer. |
| `sources` | object | No | The customer's payment sources, if any. |
| `subscriptions` | object | No | The customer's current subscriptions, if any. |
| `tax` | [customer_tax](customer-tax.md) | No |  |
| `tax_exempt` | enum: exempt, none, reverse | No | Describes the customer's tax exemption status, which is `none`, `exempt`, or `reverse`. When set to `reverse`, invoice and receipt PDFs include the following text: **"Reverse charge"**. |
| `tax_ids` | object | No | The customer's tax IDs. |
| `test_clock` | any | No | ID of the test clock that this customer belongs to. |

## Nested Fields

### `sources`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | any[] | Yes | Details about each object. |
| `has_more` | boolean | Yes | True if this list has another page of items after this one that can be fetched. |
| `object` | enum: list | Yes | String representing the object's type. Objects of the same type share the same value. Always has the value `list`. |
| `url` | string | Yes | The URL where this list can be accessed. |

### `subscriptions`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | subscription[] | Yes | Details about each object. |
| `has_more` | boolean | Yes | True if this list has another page of items after this one that can be fetched. |
| `object` | enum: list | Yes | String representing the object's type. Objects of the same type share the same value. Always has the value `list`. |
| `url` | string | Yes | The URL where this list can be accessed. |

### `tax_ids`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | tax_id[] | Yes | Details about each object. |
| `has_more` | boolean | Yes | True if this list has another page of items after this one that can be fetched. |
| `object` | enum: list | Yes | String representing the object's type. Objects of the same type share the same value. Always has the value `list`. |
| `url` | string | Yes | The URL where this list can be accessed. |


# tax_rate

Tax rates can be applied to [invoices](/invoicing/taxes/tax-rates), [subscriptions](/billing/taxes/tax-rates) and [Checkout Sessions](/payments/checkout/use-manual-tax-rates) to collect tax.

Related guide: [Tax rates](/billing/taxes/tax-rates)

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `active` | boolean | Yes | Defaults to `true`. When set to `false`, this tax rate cannot be used with new applications or Checkout Sessions, but will still work for subscriptions and invoices that already have it set. |
| `country` | string | No | Two-letter country code ([ISO 3166-1 alpha-2](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2)). |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `description` | string | No | An arbitrary string attached to the tax rate for your internal use only. It will not be visible to your customers. |
| `display_name` | string | Yes | The display name of the tax rates as it will appear to your customer on their receipt email, PDF, and the hosted invoice page. |
| `effective_percentage` | number | No | Actual/effective tax rate percentage out of 100. For tax calculations with automatic_tax[enabled]=true,
this percentage reflects the rate actually used to calculate tax based on the product's taxability
and whether the user is registered to collect taxes in the corresponding jurisdiction. |
| `flat_amount` | any | No | The amount of the tax rate when the `rate_type` is `flat_amount`. Tax rates with `rate_type` `percentage` can vary based on the transaction, resulting in this field being `null`. This field exposes the amount and currency of the flat tax rate. |
| `id` | string | Yes | Unique identifier for the object. |
| `inclusive` | boolean | Yes | This specifies if the tax rate is inclusive or exclusive. |
| `jurisdiction` | string | No | The jurisdiction for the tax rate. You can use this label field for tax reporting purposes. It also appears on your customer’s invoice. |
| `jurisdiction_level` | enum: city, country, county... | No | The level of the jurisdiction that imposes this tax rate. Will be `null` for manually defined tax rates. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `metadata` | object | No | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `object` | enum: tax_rate | Yes | String representing the object's type. Objects of the same type share the same value. |
| `percentage` | number | Yes | Tax rate percentage out of 100. For tax calculations with automatic_tax[enabled]=true, this percentage includes the statutory tax rate of non-taxable jurisdictions. |
| `rate_type` | enum: flat_amount, percentage | No | Indicates the type of tax rate applied to the taxable amount. This value can be `null` when no tax applies to the location. This field is only present for TaxRates created by Stripe Tax. |
| `state` | string | No | [ISO 3166-2 subdivision code](https://en.wikipedia.org/wiki/ISO_3166-2), without country prefix. For example, "NY" for New York, United States. |
| `tax_type` | enum: amusement_tax, communications_tax, gst... | No | The high-level tax type, such as `vat` or `sales_tax`. |


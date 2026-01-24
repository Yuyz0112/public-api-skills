# automatic_tax

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `disabled_reason` | enum: finalization_requires_location_inputs, finalization_system_error | No | If Stripe disabled automatic tax, this enum describes why. |
| `enabled` | boolean | Yes | Whether Stripe automatically computes tax on this invoice. Note that incompatible invoice items (invoice items with manually specified [tax rates](https://docs.stripe.com/api/tax_rates), negative amounts, or `tax_behavior=unspecified`) cannot be added to automatic tax invoices. |
| `liability` | any | No | The account that's liable for tax. If set, the business address and tax registrations required to perform the tax calculation are loaded from this account. The tax transaction is returned in the report of the connected account. |
| `provider` | string | No | The tax provider powering automatic tax. |
| `status` | enum: complete, failed, requires_location_inputs | No | The status of the most recent automated tax calculation for this invoice. |


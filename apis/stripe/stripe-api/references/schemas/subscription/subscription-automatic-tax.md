# subscription_automatic_tax

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `disabled_reason` | enum: requires_location_inputs | No | If Stripe disabled automatic tax, this enum describes why. |
| `enabled` | boolean | Yes | Whether Stripe automatically computes tax on this subscription. |
| `liability` | any | No | The account that's liable for tax. If set, the business address and tax registrations required to perform the tax calculation are loaded from this account. The tax transaction is returned in the report of the connected account. |


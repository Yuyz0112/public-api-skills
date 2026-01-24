# quotes_resource_automatic_tax

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | Yes | Automatically calculate taxes |
| `liability` | any | No | The account that's liable for tax. If set, the business address and tax registrations required to perform the tax calculation are loaded from this account. The tax transaction is returned in the report of the connected account. |
| `provider` | string | No | The tax provider powering automatic tax. |
| `status` | enum: complete, failed, requires_location_inputs | No | The status of the most recent automated tax calculation for this quote. |


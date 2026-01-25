# payment_method_details_paynow

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `location` | string | No | ID of the [location](https://docs.stripe.com/api/terminal/locations) that this transaction's reader is assigned to. |
| `reader` | string | No | ID of the [reader](https://docs.stripe.com/api/terminal/readers) this transaction was made on. |
| `reference` | string | No | Reference number associated with this PayNow payment |


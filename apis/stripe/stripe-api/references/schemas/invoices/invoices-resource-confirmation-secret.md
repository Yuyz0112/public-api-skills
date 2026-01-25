# invoices_resource_confirmation_secret

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `client_secret` | string | Yes | The client_secret of the payment that Stripe creates for the invoice after finalization. |
| `type` | string | Yes | The type of client_secret. Currently this is always payment_intent, referencing the default payment_intent that Stripe creates during invoice finalization |


# payment_method_details_swish

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `fingerprint` | string | No | Uniquely identifies the payer's Swish account. You can use this attribute to check whether two Swish transactions were paid for by the same payer |
| `payment_reference` | string | No | Payer bank reference number for the payment |
| `verified_phone_last4` | string | No | The last four digits of the Swish account phone number |


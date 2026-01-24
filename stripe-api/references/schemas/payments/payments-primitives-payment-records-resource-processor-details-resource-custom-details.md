# payments_primitives_payment_records_resource_processor_details_resource_custom_details

Custom processors represent payment processors not modeled directly in
the Stripe API. This resource consists of details about the custom processor
used for this payment attempt.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `payment_reference` | string | No | An opaque string for manual reconciliation of this payment, for example a check number or a payment processor ID. |


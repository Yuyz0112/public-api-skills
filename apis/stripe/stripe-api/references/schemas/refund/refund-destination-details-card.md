# refund_destination_details_card

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `reference` | string | No | Value of the reference number assigned to the refund. |
| `reference_status` | string | No | Status of the reference number on the refund. This can be `pending`, `available` or `unavailable`. |
| `reference_type` | string | No | Type of the reference number assigned to the refund. |
| `type` | enum: pending, refund, reversal | Yes | The type of refund. This can be `refund`, `reversal`, or `pending`. |


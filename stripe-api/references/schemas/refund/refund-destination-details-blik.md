# refund_destination_details_blik

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `network_decline_code` | string | No | For refunds declined by the network, a decline code provided by the network which indicates the reason the refund failed. |
| `reference` | string | No | The reference assigned to the refund. |
| `reference_status` | string | No | Status of the reference on the refund. This can be `pending`, `available` or `unavailable`. |


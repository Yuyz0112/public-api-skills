# treasury_inbound_transfers_resource_inbound_transfer_resource_status_transitions

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `canceled_at` | integer (unix-time) | No | Timestamp describing when an InboundTransfer changed status to `canceled`. |
| `failed_at` | integer (unix-time) | No | Timestamp describing when an InboundTransfer changed status to `failed`. |
| `succeeded_at` | integer (unix-time) | No | Timestamp describing when an InboundTransfer changed status to `succeeded`. |


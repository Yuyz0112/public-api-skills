# treasury_outbound_transfers_resource_status_transitions

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `canceled_at` | integer (unix-time) | No | Timestamp describing when an OutboundTransfer changed status to `canceled` |
| `failed_at` | integer (unix-time) | No | Timestamp describing when an OutboundTransfer changed status to `failed` |
| `posted_at` | integer (unix-time) | No | Timestamp describing when an OutboundTransfer changed status to `posted` |
| `returned_at` | integer (unix-time) | No | Timestamp describing when an OutboundTransfer changed status to `returned` |


# treasury_received_debits_resource_reversal_details

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `deadline` | integer (unix-time) | No | Time before which a ReceivedDebit can be reversed. |
| `restricted_reason` | enum: already_reversed, deadline_passed, network_restricted... | No | Set if a ReceivedDebit can't be reversed. |


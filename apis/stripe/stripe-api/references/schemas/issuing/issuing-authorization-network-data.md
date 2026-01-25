# issuing_authorization_network_data

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `acquiring_institution_id` | string | No | Identifier assigned to the acquirer by the card network. Sometimes this value is not provided by the network; in this case, the value will be `null`. |
| `system_trace_audit_number` | string | No | The System Trace Audit Number (STAN) is a 6-digit identifier assigned by the acquirer. Prefer `network_data.transaction_id` if present, unless you have special requirements. |
| `transaction_id` | string | No | Unique identifier for the authorization assigned by the card network used to match subsequent messages, disputes, and transactions. |


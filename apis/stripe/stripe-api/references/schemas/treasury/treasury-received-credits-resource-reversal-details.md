# treasury_received_credits_resource_reversal_details

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `deadline` | integer (unix-time) | No | Time before which a ReceivedCredit can be reversed. |
| `restricted_reason` | enum: already_reversed, deadline_passed, network_restricted... | No | Set if a ReceivedCredit cannot be reversed. |


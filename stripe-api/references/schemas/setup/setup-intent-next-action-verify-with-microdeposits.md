# setup_intent_next_action_verify_with_microdeposits

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `arrival_date` | integer (unix-time) | Yes | The timestamp when the microdeposits are expected to land. |
| `hosted_verification_url` | string | Yes | The URL for the hosted verification page, which allows customers to verify their bank account. |
| `microdeposit_type` | enum: amounts, descriptor_code | No | The type of the microdeposit sent to the customer. Used to distinguish between different verification methods. |


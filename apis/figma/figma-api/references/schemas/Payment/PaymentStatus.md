# PaymentStatus

An object describing the user's payment status.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: UNPAID, PAID, TRIAL | No | The current payment status of the user on the resource, as a string enum:
  
- `UNPAID`: user has not paid for the resource
- `PAID`: user has an active purchase on the resource
- `TRIAL`: user is in the trial period for a subscription resource |


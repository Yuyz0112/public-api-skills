# treasury_outbound_payments_resource_outbound_payment_resource_end_user_details

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `ip_address` | string | No | IP address of the user initiating the OutboundPayment. Set if `present` is set to `true`. IP address collection is required for risk and compliance reasons. This will be used to help determine if the OutboundPayment is authorized or should be blocked. |
| `present` | boolean | Yes | `true` if the OutboundPayment creation request is being made on behalf of an end user by a platform. Otherwise, `false`. |


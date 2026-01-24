# insights_resources_payment_evaluation_rejected_card

Details of an rejected card outcome attached to this payment evaluation.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `address_line1_check` | enum: fail, pass, unavailable... | Yes | Result of the address line 1 check. |
| `address_postal_code_check` | enum: fail, pass, unavailable... | Yes | Indicates whether the cardholder provided a postal code and if it matched the cardholder’s billing address. |
| `cvc_check` | enum: fail, pass, unavailable... | Yes | Result of the CVC check. |
| `reason` | enum: authentication_failed, do_not_honor, expired... | Yes | Card issuer's reason for the network decline. |


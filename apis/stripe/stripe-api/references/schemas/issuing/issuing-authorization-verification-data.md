# issuing_authorization_verification_data

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `address_line1_check` | enum: match, mismatch, not_provided | Yes | Whether the cardholder provided an address first line and if it matched the cardholder’s `billing.address.line1`. |
| `address_postal_code_check` | enum: match, mismatch, not_provided | Yes | Whether the cardholder provided a postal code and if it matched the cardholder’s `billing.address.postal_code`. |
| `authentication_exemption` | any | No | The exemption applied to this authorization. |
| `cvc_check` | enum: match, mismatch, not_provided | Yes | Whether the cardholder provided a CVC and if it matched Stripe’s record. |
| `expiry_check` | enum: match, mismatch, not_provided | Yes | Whether the cardholder provided an expiry date and if it matched Stripe’s record. |
| `postal_code` | string | No | The postal code submitted as part of the authorization used for postal code verification. |
| `three_d_secure` | any | No | 3D Secure details. |


# three_d_secure_details

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `authentication_flow` | enum: challenge, frictionless | No | For authenticated transactions: how the customer was authenticated by
the issuing bank. |
| `electronic_commerce_indicator` | enum: 01, 02, 05... | No | The Electronic Commerce Indicator (ECI). A protocol-level field
indicating what degree of authentication was performed. |
| `result` | enum: attempt_acknowledged, authenticated, exempted... | No | Indicates the outcome of 3D Secure authentication. |
| `result_reason` | enum: abandoned, bypassed, canceled... | No | Additional information about why 3D Secure succeeded or failed based
on the `result`. |
| `transaction_id` | string | No | The 3D Secure 1 XID or 3D Secure 2 Directory Server Transaction ID
(dsTransId) for this payment. |
| `version` | enum: 1.0.2, 2.1.0, 2.2.0... | No | The version of 3D Secure that was used. |


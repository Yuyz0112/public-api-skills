# invoice_payment_method_options_card

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `installments` | [invoice_installments_card](invoice-installments-card.md) | No |  |
| `request_three_d_secure` | enum: any, automatic, challenge | No | We strongly recommend that you rely on our SCA Engine to automatically prompt your customers for authentication based on risk level and [other requirements](https://docs.stripe.com/strong-customer-authentication). However, if you wish to request 3D Secure based on logic from your own fraud engine, provide this option. Read our guide on [manually requesting 3D Secure](https://docs.stripe.com/payments/3d-secure/authentication-flow#manual-three-ds) for more information on how this configuration interacts with Radar and our SCA Engine. |


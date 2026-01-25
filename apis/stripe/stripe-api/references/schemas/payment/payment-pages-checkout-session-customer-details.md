# payment_pages_checkout_session_customer_details

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `address` | any | No | The customer's address after a completed Checkout Session. Note: This property is populated only for sessions on or after March 30, 2022. |
| `business_name` | string | No | The customer's business name after a completed Checkout Session. |
| `email` | string | No | The email associated with the Customer, if one exists, on the Checkout Session after a completed Checkout Session or at time of session expiry.
Otherwise, if the customer has consented to promotional content, this value is the most recent valid email provided by the customer on the Checkout form. |
| `individual_name` | string | No | The customer's individual name after a completed Checkout Session. |
| `name` | string | No | The customer's name after a completed Checkout Session. Note: This property is populated only for sessions on or after March 30, 2022. |
| `phone` | string | No | The customer's phone number after a completed Checkout Session. |
| `tax_exempt` | enum: exempt, none, reverse | No | The customer’s tax exempt status after a completed Checkout Session. |
| `tax_ids` | payment_pages_checkout_session_tax_id[] | No | The customer’s tax IDs after a completed Checkout Session. |


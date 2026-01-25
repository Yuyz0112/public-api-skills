# issuing_dispute_canceled_evidence

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `additional_documentation` | any | No | (ID of a [file upload](https://stripe.com/docs/guides/file-upload)) Additional documentation supporting the dispute. |
| `canceled_at` | integer (unix-time) | No | Date when order was canceled. |
| `cancellation_policy_provided` | boolean | No | Whether the cardholder was provided with a cancellation policy. |
| `cancellation_reason` | string | No | Reason for canceling the order. |
| `expected_at` | integer (unix-time) | No | Date when the cardholder expected to receive the product. |
| `explanation` | string | No | Explanation of why the cardholder is disputing this transaction. |
| `product_description` | string | No | Description of the merchandise or service that was purchased. |
| `product_type` | enum: merchandise, service | No | Whether the product was a merchandise or service. |
| `return_status` | enum: merchant_rejected, successful | No | Result of cardholder's attempt to return the product. |
| `returned_at` | integer (unix-time) | No | Date when the product was returned or attempted to be returned. |


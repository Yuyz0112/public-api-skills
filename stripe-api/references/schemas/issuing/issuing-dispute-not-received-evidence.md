# issuing_dispute_not_received_evidence

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `additional_documentation` | any | No | (ID of a [file upload](https://stripe.com/docs/guides/file-upload)) Additional documentation supporting the dispute. |
| `expected_at` | integer (unix-time) | No | Date when the cardholder expected to receive the product. |
| `explanation` | string | No | Explanation of why the cardholder is disputing this transaction. |
| `product_description` | string | No | Description of the merchandise or service that was purchased. |
| `product_type` | enum: merchandise, service | No | Whether the product was a merchandise or service. |


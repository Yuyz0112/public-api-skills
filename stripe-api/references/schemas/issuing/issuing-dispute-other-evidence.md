# issuing_dispute_other_evidence

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `additional_documentation` | any | No | (ID of a [file upload](https://stripe.com/docs/guides/file-upload)) Additional documentation supporting the dispute. |
| `explanation` | string | No | Explanation of why the cardholder is disputing this transaction. |
| `product_description` | string | No | Description of the merchandise or service that was purchased. |
| `product_type` | enum: merchandise, service | No | Whether the product was a merchandise or service. |


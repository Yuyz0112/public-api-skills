# issuing_dispute_merchandise_not_as_described_evidence

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `additional_documentation` | any | No | (ID of a [file upload](https://stripe.com/docs/guides/file-upload)) Additional documentation supporting the dispute. |
| `explanation` | string | No | Explanation of why the cardholder is disputing this transaction. |
| `received_at` | integer (unix-time) | No | Date when the product was received. |
| `return_description` | string | No | Description of the cardholder's attempt to return the product. |
| `return_status` | enum: merchant_rejected, successful | No | Result of cardholder's attempt to return the product. |
| `returned_at` | integer (unix-time) | No | Date when the product was returned or attempted to be returned. |


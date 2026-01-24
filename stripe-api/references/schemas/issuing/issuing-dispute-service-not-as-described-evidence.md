# issuing_dispute_service_not_as_described_evidence

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `additional_documentation` | any | No | (ID of a [file upload](https://stripe.com/docs/guides/file-upload)) Additional documentation supporting the dispute. |
| `canceled_at` | integer (unix-time) | No | Date when order was canceled. |
| `cancellation_reason` | string | No | Reason for canceling the order. |
| `explanation` | string | No | Explanation of why the cardholder is disputing this transaction. |
| `received_at` | integer (unix-time) | No | Date when the product was received. |


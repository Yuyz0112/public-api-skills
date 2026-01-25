# issuing_dispute_duplicate_evidence

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `additional_documentation` | any | No | (ID of a [file upload](https://stripe.com/docs/guides/file-upload)) Additional documentation supporting the dispute. |
| `card_statement` | any | No | (ID of a [file upload](https://stripe.com/docs/guides/file-upload)) Copy of the card statement showing that the product had already been paid for. |
| `cash_receipt` | any | No | (ID of a [file upload](https://stripe.com/docs/guides/file-upload)) Copy of the receipt showing that the product had been paid for in cash. |
| `check_image` | any | No | (ID of a [file upload](https://stripe.com/docs/guides/file-upload)) Image of the front and back of the check that was used to pay for the product. |
| `explanation` | string | No | Explanation of why the cardholder is disputing this transaction. |
| `original_transaction` | string | No | Transaction (e.g., ipi_...) that the disputed transaction is a duplicate of. Of the two or more transactions that are copies of each other, this is original undisputed one. |


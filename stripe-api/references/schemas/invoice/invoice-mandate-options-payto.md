# invoice_mandate_options_payto

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount` | integer | No | The maximum amount that can be collected in a single invoice. If you don't specify a maximum, then there is no limit. |
| `amount_type` | enum: fixed, maximum | No | Only `maximum` is supported. |
| `purpose` | enum: dependant_support, government, loan... | No | The purpose for which payments are made. Has a default value based on your merchant category code. |


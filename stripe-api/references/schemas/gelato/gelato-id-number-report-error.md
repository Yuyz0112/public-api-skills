# gelato_id_number_report_error

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `code` | enum: id_number_insufficient_document_data, id_number_mismatch, id_number_unverified_other | No | A short machine-readable string giving the reason for the verification failure. |
| `reason` | string | No | A human-readable message giving the reason for the failure. These messages can be shown to your users. |


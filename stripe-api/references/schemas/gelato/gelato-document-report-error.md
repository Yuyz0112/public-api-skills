# gelato_document_report_error

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `code` | enum: document_expired, document_type_not_supported, document_unverified_other | No | A short machine-readable string giving the reason for the verification failure. |
| `reason` | string | No | A human-readable message giving the reason for the failure. These messages can be shown to your users. |


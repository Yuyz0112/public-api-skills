# MandatoryFieldValue

List of string of inputs

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `retain` | boolean | No | If `true`, will try to retain original non-null issue field values on move. |
| `type` | enum: adf, raw | No | Will treat as `MandatoryFieldValue` if type is `raw` or `empty` |
| `value` | string[] | Yes | Value for each field. Provide a `list of strings` for non-ADF fields. |


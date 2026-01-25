# CreateDateFieldRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `dateCustomFieldId` | integer (int64) | No | A date custom field ID. This is required if the type is "DateCustomField". |
| `type` | enum: DueDate, TargetStartDate, TargetEndDate... | Yes | The date field type. This must be "DueDate", "TargetStartDate", "TargetEndDate" or "DateCustomField". |


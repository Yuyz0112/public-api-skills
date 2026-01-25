# FieldsSchemeItemWorkTypeParameter

The list of work type-specific parameter overrides, may be empty if only default parameters are being updated

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | string | No | The custom description for the field for this work type, null to use default or preserve current |
| `isRequired` | boolean | No | Whether the field is required for this work type, null to use default or preserve current |
| `workTypeId` | integer (int64) | No | The ID of the work type (issue type) for which these parameters apply |


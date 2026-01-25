# account_requirements_alternative

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `alternative_fields_due` | string[] | Yes | Fields that can be provided to resolve all fields in `original_fields_due`. |
| `original_fields_due` | string[] | Yes | Fields that are due and can be resolved by providing all fields in `alternative_fields_due`. |


# UpdateFieldSchemeParametersRequest

Request bean for updating field scheme parameters across multiple schemes and work types.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `parameters` | [FieldsSchemeItemParameter](FieldsSchemeItemParameter.md) | No |  |
| `schemeIds` | integer[] | No | The list of field scheme IDs to update |
| `workTypeParameters` | FieldsSchemeItemWorkTypeParameter[] | No | The list of work type-specific parameter overrides, may be empty if only default parameters are being updated |


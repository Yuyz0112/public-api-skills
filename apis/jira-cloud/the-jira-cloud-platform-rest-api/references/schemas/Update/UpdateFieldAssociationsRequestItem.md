# UpdateFieldAssociationsRequestItem

Represents an association between a field and its operations.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `restrictedToWorkTypes` | integer[] | No | (optional) Work types to restrict field to. Replaces any existing work type associations for the field. If not provided, the field is associated to any work types. |
| `schemeIds` | integer[] | Yes | Scheme IDs to associate field with |


# IssueTypeHierarchyPayload

The payload for creating an issue type hierarchy

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `hierarchyLevel` | integer (int32) | No | The hierarchy level of the issue type. 0, 1, 2, 3 .. n; Negative values for subtasks |
| `name` | string | No | The name of the issue type |
| `onConflict` | enum: FAIL, USE, NEW | No | The conflict strategy to use when the issue type already exists. FAIL - Fail execution, this always needs to be unique; USE - Use the existing entity and ignore new entity parameters |
| `pcri` | [ProjectCreateResourceIdentifier](ProjectCreateResourceIdentifier.md) | No |  |


# StatusPayload

The payload for creating a status

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | string | No | The description of the status |
| `name` | string | No | The name of the status |
| `onConflict` | enum: FAIL, USE, NEW | No | The conflict strategy for the status already exists. FAIL - Fail execution, this always needs to be unique; USE - Use the existing entity and ignore new entity parameters; NEW - Create a new entity |
| `pcri` | [ProjectCreateResourceIdentifier](ProjectCreateResourceIdentifier.md) | No |  |
| `statusCategory` | enum: TODO, IN_PROGRESS, DONE | No | The status category of the status. The value is case-sensitive. |


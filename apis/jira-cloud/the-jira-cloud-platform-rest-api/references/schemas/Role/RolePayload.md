# RolePayload

The payload used to create a project role. It is optional for CMP projects, as a default role actor will be provided. TMP will add new role actors to the table.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `defaultActors` | ProjectCreateResourceIdentifier[] | No | The default actors for the role. By adding default actors, the role will be added to any future projects created |
| `description` | string | No | The description of the role |
| `name` | string | No | The name of the role |
| `onConflict` | enum: FAIL, USE, NEW | No | The strategy to use when there is a conflict with an existing project role. FAIL - Fail execution, this always needs to be unique; USE - Use the existing entity and ignore new entity parameters |
| `pcri` | [ProjectCreateResourceIdentifier](ProjectCreateResourceIdentifier.md) | No |  |
| `type` | enum: HIDDEN, VIEWABLE, EDITABLE | No | The type of the role. Only used by project-scoped project |


# VariableAlias

Contains a variable alias

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: VARIABLE_ALIAS | Yes |  |
| `id` | string | Yes | The id of the variable that the current variable is aliased to. This variable can be a local or remote variable, and both can be retrieved via the GET /v1/files/:file_key/variables/local endpoint. |


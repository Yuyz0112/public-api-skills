# pay-per-crawl_Source

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `parameter` | string | No | Parameter is a string indicating which URI query parameter caused the error. |
| `parameter_value_index` | integer | No | ParameterPosition indicates position of parameter value which caused the error,
for cases when there are multiple values for the same parameter. |
| `pointer` | string[] | No | Pointer is a JSON Pointer [RFC6901] to the associated entity in the request document
e.g. "/data" for a primary data object, or "/data/attributes/title" for a specific attribute. |


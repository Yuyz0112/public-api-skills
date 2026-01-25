# codeowners-errors

A list of errors found in a repo's CODEOWNERS file

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `errors` | object[] | Yes |  |

## Nested Fields

### `errors`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `line` | integer | Yes | The line number where this errors occurs. |
| `column` | integer | Yes | The column number where this errors occurs. |
| `source` | string | No | The contents of the line where the error occurs. |
| `kind` | string | Yes | The type of error. |
| `suggestion` | string | No | Suggested action to fix the error. This will usually be `null`, but is provided for some common errors. |
| `message` | string | Yes | A human-readable description of the error, combining information from multiple fields, laid out for display in a monospaced typeface (for example, a command-line setting). |
| `path` | string | Yes | The path of the file where the error occured. |


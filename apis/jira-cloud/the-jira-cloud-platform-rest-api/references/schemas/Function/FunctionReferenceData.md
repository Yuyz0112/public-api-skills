# FunctionReferenceData

Details of functions that can be used in advanced searches.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `displayName` | string | No | The display name of the function. |
| `isList` | enum: true, false | No | Whether the function can take a list of arguments. |
| `supportsListAndSingleValueOperators` | enum: true, false | No | Whether the function supports both single and list value operators. |
| `types` | string[] | No | The data types returned by the function. |
| `value` | string | No | The function identifier. |


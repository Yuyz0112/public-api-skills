# JqlFunctionPrecomputationBean

Jql function precomputation.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `arguments` | string[] | No | The list of arguments function was invoked with. |
| `created` | string (date-time) | No | The timestamp of the precomputation creation. |
| `error` | string | No | The error message to be displayed to the user. |
| `field` | string | No | The field the function was executed against. |
| `functionKey` | string | No | The function key. |
| `functionName` | string | No | The name of the function. |
| `id` | string | No | The id of the precomputation. |
| `operator` | string | No | The operator in context of which function was executed. |
| `updated` | string (date-time) | No | The timestamp of the precomputation last update. |
| `used` | string (date-time) | No | The timestamp of the precomputation last usage. |
| `value` | string | No | The JQL fragment stored as the precomputation. |


# FunctionOperand

An operand that is a function. See [Advanced searching - functions reference](https://confluence.atlassian.com/x/dwiiLQ) for more information about JQL functions.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `arguments` | string[] | Yes | The list of function arguments. |
| `encodedOperand` | string | No | Encoded operand, which can be used directly in a JQL query. |
| `function` | string | Yes | The name of the function. |


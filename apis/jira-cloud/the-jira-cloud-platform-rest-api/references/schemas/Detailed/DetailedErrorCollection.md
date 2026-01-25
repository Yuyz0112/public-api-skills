# DetailedErrorCollection

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `details` | object | No | Map of objects representing additional details for an error |
| `errorMessages` | string[] | No | The list of error messages produced by this operation. For example, "input parameter 'key' must be provided" |
| `errors` | object | No | The list of errors by parameter returned by the operation. For example,"projectKey": "Project keys must start with an uppercase letter, followed by one or more uppercase alphanumeric characters." |


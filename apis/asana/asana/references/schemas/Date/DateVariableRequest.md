# DateVariableRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `gid` | string | No | Globally unique identifier of the date field in the project template. A value of `1` refers to the project start date, while `2` refers to the project due date. |
| `value` | string (date-time) | No | The date with which the date variable should be replaced when instantiating a project. This takes a date with `YYYY-MM-DD` format. |


# GoalMetricCurrentValueRequest

A generic Asana Resource, containing a globally unique identifier.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `gid` | string | No | Globally unique identifier of the resource, as a string. |
| `resource_type` | string | No | The base type of this resource. |
| `current_number_value` | number | No | *Conditional*. This number is the current value of a goal metric of type number. |


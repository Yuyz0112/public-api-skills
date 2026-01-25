# AllocationBase

A generic Asana Resource, containing a globally unique identifier.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `gid` | string | No | Globally unique identifier of the resource, as a string. |
| `resource_type` | string | No | The base type of this resource. |
| `start_date` | string (date) | No | The localized day on which the allocation starts. |
| `end_date` | string (date) | No | The localized day on which the allocation ends. |
| `effort` | object | No | The amount of time associated with the allocation, represented as a percentage or number of hours. |

## Nested Fields

### `effort`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: hours, percent | No | The units used for tracking effort on an allocation, either "hours" or "percent". |
| `value` | number | No | The numeric effort value on the allocation. |


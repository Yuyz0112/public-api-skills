# RateRequest

A generic Asana Resource, containing a globally unique identifier.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `gid` | string | No | Globally unique identifier of the resource, as a string. |
| `resource_type` | string | No | The base type of this resource. |
| `parent` | string | Yes | Globally unique ID of the parent object: project. |
| `resource` | string | Yes | Globally unique ID of the resource object: user or placeholder. |
| `rate` | number | Yes | The monetary value of the rate. |


# RateCompact

A *rate* is a monetary value assigned to a resource - `user` or `placeholder` - for a given `parent` object.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `gid` | string | No | Globally unique identifier of the resource, as a string. |
| `resource_type` | string | No | The base type of this resource. |
| `parent` | [ProjectCompact](ProjectCompact.md) | No |  |
| `resource` | [UserCompact](UserCompact.md) | No |  |
| `rate` | number | No | The monetary value of the rate. |
| `currency_code` | string | No | The currency code of the rate, set at the domain level. |
| `created_by` | [UserCompact](UserCompact.md) | No |  |


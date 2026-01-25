# TimePeriodCompact

<p><strong style={{ color: "#4573D2" }}>Full object requires scope: </strong><code>time_periods:read</code></p>

A generic Asana Resource, containing a globally unique identifier.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `gid` | string | No | Globally unique identifier of the resource, as a string. |
| `resource_type` | string | No | The base type of this resource. |
| `end_on` | string | No | The localized end date of the time period in `YYYY-MM-DD` format. |
| `start_on` | string | No | The localized start date of the time period in `YYYY-MM-DD` format. |
| `period` | enum: FY, H1, H2... | No | The cadence and index of the time period. |
| `display_name` | string | No | A string representing the cadence code and the fiscal year. |


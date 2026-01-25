# AnalyticsResponderFilter

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `filters` | object | No | Accepts a set of filters to apply to the Incidents before aggregating.  Any incidents that do not match the included filters will be omitted from the results |
| `time_zone` | string | No | The time zone to use for the results and grouping. |
| `order` | enum: asc, desc | No | The order in which the results were sorted; asc for ascending, desc for descending. |
| `order_by` | string | No | The column that was used for ordering the results. |

## Nested Fields

### `filters`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `date_range_start` | string | No | Accepts an ISO8601 DateTime string. Any incidents with a created_at less than this value will be omitted from the results. The maximum supported time range in conjunction with date_range_end is one year. |
| `date_range_end` | string | No | Accepts an ISO8601 DateTime string. Any incidents with a created_at greater than or equal to this value will be omitted from the results. The maximum supported time range in conjunction with date_range_start is one year. |
| `urgency` | enum: high, low | No | Any incidents whose urgency does not match the provided string will be omitted from the results. |
| `team_ids` | string[] | No | An array of team IDs. Only incidents related to these teams will be included in the results. If omitted, all teams the requestor has access to will be included in the results. |
| `responder_ids` | string[] | No | An array of responder IDs. Only incidents related to these responders will be included in the results. If omitted, all responders the requestor has access to will be included in the results. |
| `priority_ids` | string[] | No | An array of priority IDs. Only incidents with these priorities will be included in the results. If omitted, all priorities will be included in the results. |
| `priority_names` | string[] | No | An array of user-defined priority names. Only incidents with these priorities will be included in the results. If omitted, all priorities will be included in the results. |


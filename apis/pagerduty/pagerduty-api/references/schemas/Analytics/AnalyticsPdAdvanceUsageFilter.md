# AnalyticsPdAdvanceUsageFilter

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `filters` | object | No | Accepts a set of filters to apply to the Incidents before aggregating.  Any incidents that do not match the included filters will be omitted from the results. |
| `time_zone` | string | No | The time zone to use for the results and grouping. Must be in tzdata format. See list of accepted values [here](https://en.wikipedia.org/wiki/List_of_tz_database_time_zones). |

## Nested Fields

### `filters`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created_at_start` | string | No | Accepts an ISO8601 DateTime string. Any PD Advance usage with a created_at less than this value will be omitted from the results. The maximum supported time range in conjunction with created_at_end is one year. |
| `created_at_end` | string | No | Accepts an ISO8601 DateTime string. Any PD Advance usage with a created_at greater than or equal to this value will be omitted from the results. The maximum supported time range in conjunction with created_at_start is one year. |
| `incident_created_at_start` | string | No | Accepts an ISO8601 DateTime string. Any incidents with a created_at less than this value will be omitted from the results. The maximum supported time range in conjunction with incident_created_at_end is one year. |
| `incident_created_at_end` | string | No | Accepts an ISO8601 DateTime string. Any incidents with a created_at greater than or equal to this value will be omitted from the results. The maximum supported time range in conjunction with incident_created_at_start is one year. |
| `urgency` | enum: high, low | No | Any incidents whose urgency does not match the provided string will be omitted from the results. |
| `major` | boolean | No | A boolean flag including whether results should contain *only* [major incidents](https://support.pagerduty.com/docs/operational-reviews#major-incidents), or exclude major incidents. If no value is provided all incidents will be included. |
| `min_ackowledgements` | integer | No | An integer that sets the requirement for the minimum number of acknowledgements to occur on an incident. For example, setting this to 1 will return only incidents that have at least 1 acknowledgement. If no value is provided, all incidents will be included. |
| `min_timeout_escalations` | integer | No | An integer that sets the requirement for the minimum number of timeout escalations to occur on an incident. For example, setting this to 1 will return only incidents that have at least 1 timeout escalation. If no value is provided, all incidents will be included. |
| `min_manual_escalations` | integer | No | An integer that sets the requirement for the minimum number of manual escalations to occur on an incident. For example, setting this to 1 will return only incidents that have at least 1 manual escalation. If no value is provided, all incidents will be included. |
| `team_ids` | string[] | No | An array of team IDs. Only incidents related to these teams will be included in the results. If omitted, all teams the requestor has access to will be included in the results. |
| `service_ids` | string[] | No | An array of service IDs. Only incidents related to these services will be included in the results. If omitted, all services the requestor has access to will be included in the results. |
| `escalation_policy_ids` | string[] | No | An array of escalation policy IDs. Only incidents related to these escalation policies will be included in the results. If omitted, all escalation policies the requestor has access to will be included in the results. |
| `priority_ids` | string[] | No | An array of priority IDs. Only incidents with these priorities will be included in the results. If omitted, all priorities will be included in the results. |
| `priority_names` | string[] | No | An array of user-defined priority names. Only incidents with these priorities will be included in the results. If omitted, all priorities will be included in the results. |


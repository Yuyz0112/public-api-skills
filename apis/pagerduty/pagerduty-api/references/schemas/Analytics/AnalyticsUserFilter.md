# AnalyticsUserFilter

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `filters` | [AnalyticsUserFilterConditions](AnalyticsUserFilterConditions.md) | No |  |
| `time_zone` | string | No | The time zone to use for the results and grouping. Must be in tzdata format. See list of accepted values [here](https://en.wikipedia.org/wiki/List_of_tz_database_time_zones). |
| `order` | enum: asc, desc | No | The order in which the results were sorted; asc for ascending, desc for descending. |
| `order_by` | string | No | The column that was used for ordering the results. |
| `aggregate_unit` | enum: day, week, month | No | The time unit to aggregate metrics by. If no value is provided, the metrics will be aggregated for the entire period. |
| `limit` | integer | No | The maximum number of results to return per page. The default (and maximum allowed value) is 1000. |
| `starting_after` | string | No | A cursor used for pagination. Starting after cursor provides the next set of results in forward pagination order. |
| `ending_before` | string | No | A cursor used for pagination. Ending before cursor provides the previous set of results in reverse pagination order. |


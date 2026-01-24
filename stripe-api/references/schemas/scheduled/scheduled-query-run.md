# scheduled_query_run

If you have [scheduled a Sigma query](https://docs.stripe.com/sigma/scheduled-queries), you'll
receive a `sigma.scheduled_query_run.created` webhook each time the query
runs. The webhook contains a `ScheduledQueryRun` object, which you can use to
retrieve the query results.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `data_load_time` | integer (unix-time) | Yes | When the query was run, Sigma contained a snapshot of your Stripe data at this time. |
| `error` | [sigma_scheduled_query_run_error](sigma-scheduled-query-run-error.md) | No |  |
| `file` | any | No | The file object representing the results of the query. |
| `id` | string | Yes | Unique identifier for the object. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `object` | enum: scheduled_query_run | Yes | String representing the object's type. Objects of the same type share the same value. |
| `result_available_until` | integer (unix-time) | Yes | Time at which the result expires and is no longer available for download. |
| `sql` | string | Yes | SQL for the query. |
| `status` | string | Yes | The query's execution status, which will be `completed` for successful runs, and `canceled`, `failed`, or `timed_out` otherwise. |
| `title` | string | Yes | Title of the query. |


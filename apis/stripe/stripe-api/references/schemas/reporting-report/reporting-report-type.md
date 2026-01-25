# reporting.report_type

The Report Type resource corresponds to a particular type of report, such as
the "Activity summary" or "Itemized payouts" reports. These objects are
identified by an ID belonging to a set of enumerated values. See
[API Access to Reports documentation](https://docs.stripe.com/reporting/statements/api)
for those Report Type IDs, along with required and optional parameters.

Note that certain report types can only be run based on your live-mode data (not test-mode
data), and will error when queried without a [live-mode API key](https://docs.stripe.com/keys#test-live-modes).

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data_available_end` | integer (unix-time) | Yes | Most recent time for which this Report Type is available. Measured in seconds since the Unix epoch. |
| `data_available_start` | integer (unix-time) | Yes | Earliest time for which this Report Type is available. Measured in seconds since the Unix epoch. |
| `default_columns` | string[] | No | List of column names that are included by default when this Report Type gets run. (If the Report Type doesn't support the `columns` parameter, this will be null.) |
| `id` | string | Yes | The [ID of the Report Type](https://docs.stripe.com/reporting/statements/api#available-report-types), such as `balance.summary.1`. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `name` | string | Yes | Human-readable name of the Report Type |
| `object` | enum: reporting.report_type | Yes | String representing the object's type. Objects of the same type share the same value. |
| `updated` | integer (unix-time) | Yes | When this Report Type was latest updated. Measured in seconds since the Unix epoch. |
| `version` | integer | Yes | Version of the Report Type. Different versions report with the same ID will have the same purpose, but may take different run parameters or have different result schemas. |


# financial_reporting_finance_report_run_run_parameters

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `columns` | string[] | No | The set of output columns requested for inclusion in the report run. |
| `connected_account` | string | No | Connected account ID by which to filter the report run. |
| `currency` | string (currency) | No | Currency of objects to be included in the report run. |
| `interval_end` | integer (unix-time) | No | Ending timestamp of data to be included in the report run. Can be any UTC timestamp between 1 second after the user specified `interval_start` and 1 second before this report's last `data_available_end` value. |
| `interval_start` | integer (unix-time) | No | Starting timestamp of data to be included in the report run. Can be any UTC timestamp between 1 second after this report's `data_available_start` and 1 second before the user specified `interval_end` value. |
| `payout` | string | No | Payout ID by which to filter the report run. |
| `reporting_category` | string | No | Category of balance transactions to be included in the report run. |
| `timezone` | string | No | Defaults to `Etc/UTC`. The output timezone for all timestamps in the report. A list of possible time zone values is maintained at the [IANA Time Zone Database](http://www.iana.org/time-zones). Has no effect on `interval_start` or `interval_end`. |


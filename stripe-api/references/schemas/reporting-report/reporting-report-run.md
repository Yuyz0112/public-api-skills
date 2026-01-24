# reporting.report_run

The Report Run object represents an instance of a report type generated with
specific run parameters. Once the object is created, Stripe begins processing the report.
When the report has finished running, it will give you a reference to a file
where you can retrieve your results. For an overview, see
[API Access to Reports](https://docs.stripe.com/reporting/statements/api).

Note that certain report types can only be run based on your live-mode data (not test-mode
data), and will error when queried without a [live-mode API key](https://docs.stripe.com/keys#test-live-modes).

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `error` | string | No | If something should go wrong during the run, a message about the failure (populated when
 `status=failed`). |
| `id` | string | Yes | Unique identifier for the object. |
| `livemode` | boolean | Yes | `true` if the report is run on live mode data and `false` if it is run on test mode data. |
| `object` | enum: reporting.report_run | Yes | String representing the object's type. Objects of the same type share the same value. |
| `parameters` | [financial_reporting_finance_report_run_run_parameters](financial-reporting-finance-report-run-run-parameters.md) | Yes |  |
| `report_type` | string | Yes | The ID of the [report type](https://docs.stripe.com/reports/report-types) to run, such as `"balance.summary.1"`. |
| `result` | any | No | The file object representing the result of the report run (populated when
 `status=succeeded`). |
| `status` | string | Yes | Status of this report run. This will be `pending` when the run is initially created.
 When the run finishes, this will be set to `succeeded` and the `result` field will be populated.
 Rarely, we may encounter an error, at which point this will be set to `failed` and the `error` field will be populated. |
| `succeeded_at` | integer (unix-time) | No | Timestamp at which this run successfully finished (populated when
 `status=succeeded`). Measured in seconds since the Unix epoch. |


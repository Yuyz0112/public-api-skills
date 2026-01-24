# payouts_trace_id

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `status` | string | Yes | Possible values are `pending`, `supported`, and `unsupported`. When `payout.status` is `pending` or `in_transit`, this will be `pending`. When the payout transitions to `paid`, `failed`, or `canceled`, this status will become `supported` or `unsupported` shortly after in most cases. In some cases, this may appear as `pending` for up to 10 days after `arrival_date` until transitioning to `supported` or `unsupported`. |
| `value` | string | No | The trace ID value if `trace_id.status` is `supported`, otherwise `nil`. |


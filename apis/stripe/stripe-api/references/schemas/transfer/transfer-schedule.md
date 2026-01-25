# transfer_schedule

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `delay_days` | integer | Yes | The number of days charges for the account will be held before being paid out. |
| `interval` | string | Yes | How frequently funds will be paid out. One of `manual` (payouts only created via API call), `daily`, `weekly`, or `monthly`. |
| `monthly_anchor` | integer | No | The day of the month funds will be paid out. Only shown if `interval` is monthly. Payouts scheduled between the 29th and 31st of the month are sent on the last day of shorter months. |
| `monthly_payout_days` | integer[] | No | The days of the month funds will be paid out. Only shown if `interval` is monthly. Payouts scheduled between the 29th and 31st of the month are sent on the last day of shorter months. |
| `weekly_anchor` | string | No | The day of the week funds will be paid out, of the style 'monday', 'tuesday', etc. Only shown if `interval` is weekly. |
| `weekly_payout_days` | string[] | No | The days of the week when available funds are paid out, specified as an array, for example, [`monday`, `tuesday`]. Only shown if `interval` is weekly. |


# Usage data

Operations related to usage data.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v4/usage_data/queries` | Get raw SQL queries for usage data SQL metrics | [View](../operations/getApiV4UsageDataQueries.md) |
| GET | `/api/v4/usage_data/non_sql_metrics` | Get Non SQL usage ping metrics | [View](../operations/getApiV4UsageDataNonSqlMetrics.md) |
| POST | `/api/v4/usage_data/increment_counter` | Track usage data event | [View](../operations/postApiV4UsageDataIncrementCounter.md) |
| POST | `/api/v4/usage_data/increment_unique_users` | Track usage data event for the current user | [View](../operations/postApiV4UsageDataIncrementUniqueUsers.md) |
| POST | `/api/v4/usage_data/track_events` | Track multiple gitlab internal events | [View](../operations/postApiV4UsageDataTrackEvents.md) |
| GET | `/api/v4/usage_data/service_ping` | Get the latest ServicePing payload | [View](../operations/getApiV4UsageDataServicePing.md) |
| POST | `/api/v4/usage_data/track_event` | Track gitlab internal events | [View](../operations/postApiV4UsageDataTrackEvent.md) |

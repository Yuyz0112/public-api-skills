# GET /api/v4/groups/{id}/dora/metrics

**Resource:** [DORA metrics](../resources/DORA-metrics.md)
**Get group-level DORA metrics**
**Operation ID:** `getApiV4GroupsIdDoraMetrics`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of the group |
| `metric` | query | string | Yes | One of `deployment_frequency`, `lead_time_for_changes`, `time_to_restore_service` or `change_failure_rate` |
| `start_date` | query | string (date) | No | Date range to start from. ISO 8601 Date format, for example `2021-03-01`. Default is 3 months ago |
| `end_date` | query | string (date) | No | Date range to end at. ISO 8601 Date format, for example `2021-03-01`. Default is the current date |
| `interval` | query | string | No | The bucketing interval. One of `all`, `monthly` or `daily`. Default is `daily` |
| `environment_tiers` | query | any | No | The tiers of the environments. Default is `production` |

## Responses

| Status | Description |
|--------|-------------|
| 200 | successful operation |
| 400 | Bad request |
| 401 | Unauthorized |


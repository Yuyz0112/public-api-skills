# GET /v1/activity_logs

**Resource:** [Activity Logs](../resources/Activity-Logs.md)
**Get activity logs**
**Operation ID:** `getActivityLogs`

Returns a list of activity log events

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `events` | query | string | No | Event type(s) to include in the response. Can have multiple values separated by comma. All events are returned by default. |
| `start_time` | query | number | No | Unix timestamp of the least recent event to include. This param defaults to one year ago if unspecified. |
| `end_time` | query | number | No | Unix timestamp of the most recent event to include. This param defaults to the current timestamp if unspecified. |
| `limit` | query | number | No | Maximum number of events to return. This param defaults to 1000 if unspecified. |
| `order` | query | enum: asc, desc | No | Event order by timestamp. This param can be either "asc" (default) or "desc". |

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 429 | (reference) |
| 500 | (reference) |

## Security

- **OrgOAuth2**: org:activity_log_read

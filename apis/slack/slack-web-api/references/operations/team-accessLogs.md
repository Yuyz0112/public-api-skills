# GET /team.accessLogs

**Resource:** [team](../resources/team.md)
**Operation ID:** `team_accessLogs`

Gets the access logs for the current team.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | query | string | Yes | Authentication token. Requires scope: `admin` |
| `before` | query | string | No | End of time range of logs to include in results (inclusive). |
| `count` | query | string | No |  |
| `page` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | This response demonstrates pagination and two access log entries. |
| default | A workspace must be on a paid plan to use this method, otherwise the `paid_only` error is thrown: |

## Security

- **slackAuth**: admin

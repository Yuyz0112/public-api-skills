# GET /team.billableInfo

**Resource:** [team](../resources/team.md)
**Operation ID:** `team_billableInfo`

Gets billable users information for the current team.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | query | string | Yes | Authentication token. Requires scope: `admin` |
| `user` | query | string | No | A user to retrieve the billable information for. Defaults to all users. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: admin

# GET /admin.inviteRequests.denied.list

**Resource:** [admin.inviteRequests.denied](../resources/admin-inviteRequests-denied.md)
**Operation ID:** `admin_inviteRequests_denied_list`

List all denied workspace invite requests.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | header | string | Yes | Authentication token. Requires scope: `admin.invites:read` |
| `team_id` | query | string | No | ID for the workspace where the invite requests were made. |
| `cursor` | query | string | No | Value of the `next_cursor` field sent as part of the previous api response |
| `limit` | query | integer | No | The number of results that will be returned by the API on each invocation. Must be between 1 - 1000 both inclusive |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: admin.invites:read

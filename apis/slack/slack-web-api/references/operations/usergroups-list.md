# GET /usergroups.list

**Resource:** [usergroups](../resources/usergroups.md)
**Operation ID:** `usergroups_list`

List all User Groups for a team

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `include_users` | query | boolean | No | Include the list of users for each User Group. |
| `token` | query | string | Yes | Authentication token. Requires scope: `usergroups:read` |
| `include_count` | query | boolean | No | Include the number of users in each User Group. |
| `include_disabled` | query | boolean | No | Include disabled User Groups. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: usergroups:read

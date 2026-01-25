# GET /admin.usergroups.listChannels

**Resource:** [admin.usergroups](../resources/admin-usergroups.md)
**Operation ID:** `admin_usergroups_listChannels`

List the channels linked to an org-level IDP group (user group).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | header | string | Yes | Authentication token. Requires scope: `admin.usergroups:read` |
| `usergroup_id` | query | string | Yes | ID of the IDP group to list default channels for. |
| `team_id` | query | string | No | ID of the the workspace. |
| `include_num_members` | query | boolean | No | Flag to include or exclude the count of members per channel. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response if the token provided is not associated with an Org Admin or Owner |

## Security

- **slackAuth**: admin.usergroups:read

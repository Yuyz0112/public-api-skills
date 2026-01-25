# GET /usergroups.users.list

**Resource:** [usergroups.users](../resources/usergroups-users.md)
**Operation ID:** `usergroups_users_list`

List all users in a User Group

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | query | string | Yes | Authentication token. Requires scope: `usergroups:read` |
| `include_disabled` | query | boolean | No | Allow results that involve disabled User Groups. |
| `usergroup` | query | string | Yes | The encoded ID of the User Group to update. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Standard success response when used with a user token |
| default | Standard failure response when used with an invalid token |

## Security

- **slackAuth**: usergroups:read

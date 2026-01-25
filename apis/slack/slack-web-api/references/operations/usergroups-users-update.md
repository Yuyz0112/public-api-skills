# POST /usergroups.users.update

**Resource:** [usergroups.users](../resources/usergroups-users.md)
**Operation ID:** `usergroups_users_update`

Update the list of users for a User Group

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | header | string | Yes | Authentication token. Requires scope: `usergroups:write` |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: usergroups:write

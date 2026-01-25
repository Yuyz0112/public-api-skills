# POST /admin.usergroups.removeChannels

**Resource:** [admin.usergroups](../resources/admin-usergroups.md)
**Operation ID:** `admin_usergroups_removeChannels`

Remove one or more default channels from an org-level IDP group (user group).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | header | string | Yes | Authentication token. Requires scope: `admin.usergroups:write` |

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response if the token provided is not associated with an Org Admin or Owner |

## Security

- **slackAuth**: admin.usergroups:write

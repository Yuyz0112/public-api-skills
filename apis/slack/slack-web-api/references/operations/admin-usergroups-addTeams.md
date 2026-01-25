# POST /admin.usergroups.addTeams

**Resource:** [admin.usergroups](../resources/admin-usergroups.md)
**Operation ID:** `admin_usergroups_addTeams`

Associate one or more default workspaces with an organization-wide IDP group.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | header | string | Yes | Authentication token. Requires scope: `admin.teams:write` |

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: admin.teams:write

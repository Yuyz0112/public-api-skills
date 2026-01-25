# POST /usergroups.enable

**Resource:** [usergroups](../resources/usergroups.md)
**Operation ID:** `usergroups_enable`

Enable a User Group

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

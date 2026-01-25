# POST /admin.inviteRequests.approve

**Resource:** [admin.inviteRequests](../resources/admin-inviteRequests.md)
**Operation ID:** `admin_inviteRequests_approve`

Approve a workspace invite request.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | header | string | Yes | Authentication token. Requires scope: `admin.invites:write` |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: admin.invites:write

# POST /api/v4/users/{id}/support_pin/revoke

**Resource:** [Support pins](../resources/Support-pins.md)
**Revoke support PIN for a user. Available only for admins.**
**Operation ID:** `postApiV4UsersIdSupportPinRevoke`

This feature allows administrators to revoke the support PIN for a specified user before its natural expiration

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | The ID of the user |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |


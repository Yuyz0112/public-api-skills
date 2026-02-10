# GET /api/v4/users/{id}/support_pin

**Resource:** [Support pins](../resources/Support-pins.md)
**Get support PIN for a user. Available only for admins.**
**Operation ID:** `getApiV4UsersIdSupportPin`

This feature allows administrators to retrieve the support PIN for a specified user

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | The ID of the user |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesUserSupportPin](../schemas/APIEntitiesUserSupportPin/APIEntitiesUserSupportPin.md)


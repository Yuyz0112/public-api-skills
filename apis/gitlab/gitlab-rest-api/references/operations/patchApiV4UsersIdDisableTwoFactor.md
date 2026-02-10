# PATCH /api/v4/users/{id}/disable_two_factor

**Resource:** [Users](../resources/Users.md)
**Disable two factor authentication for a user. Available only for admins**
**Operation ID:** `patchApiV4UsersIdDisableTwoFactor`

This feature was added in GitLab 15.2

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | The ID of the user |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesUserWithAdmin](../schemas/APIEntitiesUserWithAdmin/APIEntitiesUserWithAdmin.md)


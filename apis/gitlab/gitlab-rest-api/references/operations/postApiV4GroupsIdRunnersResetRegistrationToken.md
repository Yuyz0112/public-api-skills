# POST /api/v4/groups/{id}/runners/reset_registration_token

**Resource:** [Runners](../resources/Runners.md)
**Reset runner registration token**
**Operation ID:** `postApiV4GroupsIdRunnersResetRegistrationToken`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Group Not Found |

**Success Response Schema:**

[APIEntitiesCiResetTokenResult](../schemas/APIEntitiesCiResetTokenResult/APIEntitiesCiResetTokenResult.md)


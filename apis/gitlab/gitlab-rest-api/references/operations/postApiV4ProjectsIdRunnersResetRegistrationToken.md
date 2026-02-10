# POST /api/v4/projects/{id}/runners/reset_registration_token

**Resource:** [Runners](../resources/Runners.md)
**Reset runner registration token**
**Operation ID:** `postApiV4ProjectsIdRunnersResetRegistrationToken`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a project |

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Project Not Found |

**Success Response Schema:**

[APIEntitiesCiResetTokenResult](../schemas/APIEntitiesCiResetTokenResult/APIEntitiesCiResetTokenResult.md)


# POST /api/v4/runners/{id}/reset_authentication_token

**Resource:** [Runners](../resources/Runners.md)
**Reset runner authentication token**
**Operation ID:** `postApiV4RunnersIdResetAuthenticationToken`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | The ID of the runner |

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 403 | No access granted |
| 404 | Runner not found |

**Success Response Schema:**

[APIEntitiesCiResetTokenResult](../schemas/APIEntitiesCiResetTokenResult/APIEntitiesCiResetTokenResult.md)


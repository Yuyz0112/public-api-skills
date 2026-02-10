# POST /api/v4/runners/reset_authentication_token

**Resource:** [CI runners](../resources/CI-runners.md)
**Reset runner authentication token with current token**
**Operation ID:** `postApiV4RunnersResetAuthenticationToken`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 403 | Forbidden |

**Success Response Schema:**

[APIEntitiesCiResetTokenResult](../schemas/APIEntitiesCiResetTokenResult/APIEntitiesCiResetTokenResult.md)


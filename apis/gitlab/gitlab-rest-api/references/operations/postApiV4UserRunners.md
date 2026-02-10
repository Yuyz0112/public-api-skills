# POST /api/v4/user/runners

**Resource:** [User](../resources/User.md)
**Create a runner owned by currently authenticated user**
**Operation ID:** `postApiV4UserRunners`

Create a new runner

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | Bad Request |
| 403 | Forbidden |

**Success Response Schema:**

[APIEntitiesCiRunnerRegistrationDetails](../schemas/APIEntitiesCiRunnerRegistrationDetails/APIEntitiesCiRunnerRegistrationDetails.md)


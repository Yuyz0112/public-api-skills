# POST /api/v4/runners

**Resource:** [CI runners](../resources/CI-runners.md)
**Register a new runner**
**Operation ID:** `postApiV4Runners`

Register a new runner for the instance

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | Bad Request |
| 403 | Forbidden |
| 410 | Gone |

**Success Response Schema:**

[APIEntitiesCiRunnerRegistrationDetails](../schemas/APIEntitiesCiRunnerRegistrationDetails/APIEntitiesCiRunnerRegistrationDetails.md)


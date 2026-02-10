# POST /api/v4/features/{name}

**Resource:** [Features](../resources/Features.md)
**Set or create a feature**
**Operation ID:** `postApiV4FeaturesName`

Set a feature's gate value. If a feature with the given name doesn't exist yet, it's created. The value can be a boolean, or an integer to indicate percentage of time.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | Bad request |
| 401 | Unauthorized |
| 403 | Forbidden |

**Success Response Schema:**

[APIEntitiesFeature](../schemas/APIEntitiesFeature/APIEntitiesFeature.md)


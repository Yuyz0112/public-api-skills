# POST /api/v4/projects/{id}/feature_flags

**Resource:** [Feature flags](../resources/Feature-flags.md)
**Create a new feature flag**
**Operation ID:** `postApiV4ProjectsIdFeatureFlags`

Creates a new feature flag. This feature was introduced in GitLab 12.5.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

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

[APIEntitiesFeatureFlag](../schemas/APIEntitiesFeatureFlag/APIEntitiesFeatureFlag.md)


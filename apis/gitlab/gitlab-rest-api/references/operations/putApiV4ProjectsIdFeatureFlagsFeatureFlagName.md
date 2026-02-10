# PUT /api/v4/projects/{id}/feature_flags/{feature_flag_name}

**Resource:** [Feature flags](../resources/Feature-flags.md)
**Update a feature flag**
**Operation ID:** `putApiV4ProjectsIdFeatureFlagsFeatureFlagName`

Updates a feature flag. This feature was introduced in GitLab 13.2.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `feature_flag_name` | path | string | Yes | The name of the feature flag |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |
| 422 | Unprocessable entity |

**Success Response Schema:**

[APIEntitiesFeatureFlag](../schemas/APIEntitiesFeatureFlag/APIEntitiesFeatureFlag.md)


# GET /api/v4/projects/{id}/feature_flags/{feature_flag_name}

**Resource:** [Feature flags](../resources/Feature-flags.md)
**Get a single feature flag**
**Operation ID:** `getApiV4ProjectsIdFeatureFlagsFeatureFlagName`

Gets a single feature flag. This feature was introduced in GitLab 12.5.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `feature_flag_name` | path | string | Yes | The name of the feature flag |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesFeatureFlag](../schemas/APIEntitiesFeatureFlag/APIEntitiesFeatureFlag.md)


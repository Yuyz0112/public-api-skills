# GET /api/v4/projects/{id}/feature_flags

**Resource:** [Feature flags](../resources/Feature-flags.md)
**List feature flags for a project**
**Operation ID:** `getApiV4ProjectsIdFeatureFlags`

Gets all feature flags of the requested project. This feature was introduced in GitLab 12.5.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `scope` | query | enum: enabled, disabled | No | The scope of feature flags, one of: `enabled`, `disabled` |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesFeatureFlag](../schemas/APIEntitiesFeatureFlag/APIEntitiesFeatureFlag.md)


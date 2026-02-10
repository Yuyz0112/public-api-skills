# GET /api/v4/projects/{id}/feature_flags_user_lists

**Resource:** [Feature flags](../resources/Feature-flags.md)
**List all feature flag user lists for a project**
**Operation ID:** `getApiV4ProjectsIdFeatureFlagsUserLists`

Gets all feature flag user lists for the requested project. This feature was introduced in GitLab 12.10.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `search` | query | string | No | Return user lists matching the search criteria |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesFeatureFlagUserList](../schemas/APIEntitiesFeatureFlagUserList/APIEntitiesFeatureFlagUserList.md)


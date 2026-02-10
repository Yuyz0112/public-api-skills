# POST /api/v4/projects/{id}/feature_flags_user_lists

**Resource:** [Feature flags](../resources/Feature-flags.md)
**Create a feature flag user list**
**Operation ID:** `postApiV4ProjectsIdFeatureFlagsUserLists`

Creates a feature flag user list. This feature was introduced in GitLab 12.10.

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
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesFeatureFlagUserList](../schemas/APIEntitiesFeatureFlagUserList/APIEntitiesFeatureFlagUserList.md)


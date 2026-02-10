# GET /api/v4/projects/{id}/feature_flags_user_lists/{iid}

**Resource:** [Feature flags](../resources/Feature-flags.md)
**Get a feature flag user list**
**Operation ID:** `getApiV4ProjectsIdFeatureFlagsUserListsIid`

Gets a feature flag user list. This feature was introduced in GitLab 12.10.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `iid` | path | any | Yes | The internal ID of the project's feature flag user list |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesFeatureFlagUserList](../schemas/APIEntitiesFeatureFlagUserList/APIEntitiesFeatureFlagUserList.md)


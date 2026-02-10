# DELETE /api/v4/projects/{id}/feature_flags_user_lists/{iid}

**Resource:** [Feature flags](../resources/Feature-flags.md)
**Delete feature flag user list**
**Operation ID:** `deleteApiV4ProjectsIdFeatureFlagsUserListsIid`

Deletes a feature flag user list. This feature was introduced in GitLab 12.10.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `iid` | path | any | Yes | The internal ID of the project's feature flag user list |

## Responses

| Status | Description |
|--------|-------------|
| 401 | Unauthorized |
| 404 | Not found |
| 409 | Conflict |


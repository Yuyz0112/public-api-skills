# DELETE /api/v4/projects/{id}/feature_flags/{feature_flag_name}

**Resource:** [Feature flags](../resources/Feature-flags.md)
**Delete a feature flag**
**Operation ID:** `deleteApiV4ProjectsIdFeatureFlagsFeatureFlagName`

Deletes a feature flag. This feature was introduced in GitLab 12.5.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `feature_flag_name` | path | string | Yes | The name of the feature flag |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |


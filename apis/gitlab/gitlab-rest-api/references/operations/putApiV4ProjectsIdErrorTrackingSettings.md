# PUT /api/v4/projects/{id}/error_tracking/settings

**Resource:** [Error tracking](../resources/Error-tracking.md)
**Update Error Tracking project settings. Available in GitLab 15.10 and later.**
**Operation ID:** `putApiV4ProjectsIdErrorTrackingSettings`

Update Error Tracking settings for a project. Only for users with Maintainer role for the project.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project owned by the authenticated user |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesErrorTrackingProjectSetting](../schemas/APIEntitiesErrorTrackingProjectSetting/APIEntitiesErrorTrackingProjectSetting.md)


# GET /api/v4/projects/{id}/error_tracking/settings

**Resource:** [Error tracking](../resources/Error-tracking.md)
**Get Error Tracking settings**
**Operation ID:** `getApiV4ProjectsIdErrorTrackingSettings`

Get error tracking settings for the project. This feature was introduced in GitLab 12.7.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project owned by the authenticated user |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesErrorTrackingProjectSetting](../schemas/APIEntitiesErrorTrackingProjectSetting/APIEntitiesErrorTrackingProjectSetting.md)


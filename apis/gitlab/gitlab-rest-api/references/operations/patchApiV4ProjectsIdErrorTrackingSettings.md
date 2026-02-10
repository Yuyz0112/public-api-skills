# PATCH /api/v4/projects/{id}/error_tracking/settings

**Resource:** [Error tracking](../resources/Error-tracking.md)
**Enable or disable the Error Tracking project settings**
**Operation ID:** `patchApiV4ProjectsIdErrorTrackingSettings`

The API allows you to enable or disable the Error Tracking settings for a project.Only for users with the Maintainer role for the project.

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


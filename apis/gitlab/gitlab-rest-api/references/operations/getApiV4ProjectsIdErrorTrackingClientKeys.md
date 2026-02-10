# GET /api/v4/projects/{id}/error_tracking/client_keys

**Resource:** [Error tracking](../resources/Error-tracking.md)
**List project client keys**
**Operation ID:** `getApiV4ProjectsIdErrorTrackingClientKeys`

List all client keys. This feature was introduced in GitLab 14.3.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project owned by the authenticated user |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesErrorTrackingClientKey](../schemas/APIEntitiesErrorTrackingClientKey/APIEntitiesErrorTrackingClientKey.md)


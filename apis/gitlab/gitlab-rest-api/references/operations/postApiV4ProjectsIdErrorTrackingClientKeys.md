# POST /api/v4/projects/{id}/error_tracking/client_keys

**Resource:** [Error tracking](../resources/Error-tracking.md)
**Create a client key**
**Operation ID:** `postApiV4ProjectsIdErrorTrackingClientKeys`

Creates a new client key for a project. The public key attribute is generated automatically.This feature was introduced in GitLab 14.3.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project owned by the authenticated user |

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesErrorTrackingClientKey](../schemas/APIEntitiesErrorTrackingClientKey/APIEntitiesErrorTrackingClientKey.md)


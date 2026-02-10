# POST /api/v4/projects/{id}/access_requests

**Resource:** [Access requests](../resources/Access-requests.md)
**Requests access for the authenticated user to a project.**
**Operation ID:** `postApiV4ProjectsIdAccessRequests`

This feature was introduced in GitLab 8.11.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID or URL-encoded path of the project owned by the authenticated user |

## Responses

| Status | Description |
|--------|-------------|
| 200 | successful operation |

**Success Response Schema:**

[APIEntitiesAccessRequester](../schemas/APIEntitiesAccessRequester/APIEntitiesAccessRequester.md)


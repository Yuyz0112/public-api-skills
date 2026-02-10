# GET /api/v4/projects/{id}/access_requests

**Resource:** [Access requests](../resources/Access-requests.md)
**Gets a list of access requests for a project.**
**Operation ID:** `getApiV4ProjectsIdAccessRequests`

This feature was introduced in GitLab 8.11.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID or URL-encoded path of the project owned by the authenticated user |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesAccessRequester](../schemas/APIEntitiesAccessRequester/APIEntitiesAccessRequester.md)


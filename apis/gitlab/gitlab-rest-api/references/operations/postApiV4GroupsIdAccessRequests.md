# POST /api/v4/groups/{id}/access_requests

**Resource:** [Access requests](../resources/Access-requests.md)
**Requests access for the authenticated user to a group.**
**Operation ID:** `postApiV4GroupsIdAccessRequests`

This feature was introduced in GitLab 8.11.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID or URL-encoded path of the group owned by the authenticated user |

## Responses

| Status | Description |
|--------|-------------|
| 200 | successful operation |

**Success Response Schema:**

[APIEntitiesAccessRequester](../schemas/APIEntitiesAccessRequester/APIEntitiesAccessRequester.md)


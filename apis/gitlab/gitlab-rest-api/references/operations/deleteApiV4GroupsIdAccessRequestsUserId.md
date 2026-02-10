# DELETE /api/v4/groups/{id}/access_requests/{user_id}

**Resource:** [Access requests](../resources/Access-requests.md)
**Denies an access request for the given user.**
**Operation ID:** `deleteApiV4GroupsIdAccessRequestsUserId`

This feature was introduced in GitLab 8.11.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID or URL-encoded path of the group owned by the authenticated user |
| `user_id` | path | integer | Yes | The user ID of the access requester |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |


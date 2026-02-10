# PUT /api/v4/groups/{id}/access_requests/{user_id}/approve

**Resource:** [Access requests](../resources/Access-requests.md)
**Approves an access request for the given user.**
**Operation ID:** `putApiV4GroupsIdAccessRequestsUserIdApprove`

This feature was introduced in GitLab 8.11.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID or URL-encoded path of the group owned by the authenticated user |
| `user_id` | path | integer | Yes | The user ID of the access requester |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | successful operation |

**Success Response Schema:**

[APIEntitiesAccessRequester](../schemas/APIEntitiesAccessRequester/APIEntitiesAccessRequester.md)


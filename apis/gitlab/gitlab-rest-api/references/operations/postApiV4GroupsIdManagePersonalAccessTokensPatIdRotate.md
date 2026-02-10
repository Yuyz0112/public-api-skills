# POST /api/v4/groups/{id}/manage/personal_access_tokens/{pat_id}/rotate

**Resource:** [Group credentials inventory](../resources/Group-credentials-inventory.md)
**Rotate personal access token**
**Operation ID:** `postApiV4GroupsIdManagePersonalAccessTokensPatIdRotate`

Rotates a personal access token.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | ID or URL-encoded path of the group |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesPersonalAccessTokenWithToken](../schemas/APIEntitiesPersonalAccessTokenWithToken/APIEntitiesPersonalAccessTokenWithToken.md)


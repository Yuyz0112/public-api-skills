# DELETE /api/v4/groups/{id}/manage/personal_access_tokens/{pat_id}

**Resource:** [Group credentials inventory](../resources/Group-credentials-inventory.md)
**Revoke a personal access token for the group**
**Operation ID:** `deleteApiV4GroupsIdManagePersonalAccessTokensPatId`

Revoke a personal access token by using the ID of the personal access token.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | ID or URL-encoded path of the group |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 400 | Bad Request |


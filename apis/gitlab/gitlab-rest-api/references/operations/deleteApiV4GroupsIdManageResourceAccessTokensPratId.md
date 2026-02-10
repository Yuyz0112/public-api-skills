# DELETE /api/v4/groups/{id}/manage/resource_access_tokens/{prat_id}

**Resource:** [Group credentials inventory](../resources/Group-credentials-inventory.md)
**Revoke a resource access token for the group**
**Operation ID:** `deleteApiV4GroupsIdManageResourceAccessTokensPratId`

Revoke a resource access token by using the ID of the resource access token.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expires_at` | query | string (date) | No | The expiration date of the token |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 400 | Bad Request |


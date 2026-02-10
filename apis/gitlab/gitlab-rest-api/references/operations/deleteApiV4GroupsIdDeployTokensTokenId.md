# DELETE /api/v4/groups/{id}/deploy_tokens/{token_id}

**Resource:** [Deploy resources](../resources/Deploy-resources.md)
**Delete a group deploy token**
**Operation ID:** `deleteApiV4GroupsIdDeployTokensTokenId`

Removes a deploy token from the group. This feature was introduced in GitLab 12.9.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the group owned by the authenticated user |
| `token_id` | path | integer | Yes | The ID of the deploy token |

## Responses

| Status | Description |
|--------|-------------|
| 401 | Unauthorized |
| 404 | Not found |


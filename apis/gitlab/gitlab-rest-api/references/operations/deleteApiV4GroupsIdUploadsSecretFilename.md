# DELETE /api/v4/groups/{id}/uploads/{secret}/{filename}

**Resource:** [Groups](../resources/Groups.md)
**Delete a single group upload by secret and filename**
**Operation ID:** `deleteApiV4GroupsIdUploadsSecretFilename`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `secret` | path | string | Yes | The 32-character secret of a group upload |
| `filename` | path | string | Yes | The filename of a group upload |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 400 | Bad request |
| 403 | Unauthenticated |
| 404 | Not found |


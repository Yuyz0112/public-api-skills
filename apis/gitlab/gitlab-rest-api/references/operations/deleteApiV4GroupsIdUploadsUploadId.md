# DELETE /api/v4/groups/{id}/uploads/{upload_id}

**Resource:** [Groups](../resources/Groups.md)
**Delete a single group upload**
**Operation ID:** `deleteApiV4GroupsIdUploadsUploadId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `upload_id` | path | integer | Yes | The ID of a group upload |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 400 | Bad request |
| 403 | Unauthenticated |
| 404 | Not found |


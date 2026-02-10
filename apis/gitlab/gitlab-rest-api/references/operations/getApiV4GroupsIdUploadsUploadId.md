# GET /api/v4/groups/{id}/uploads/{upload_id}

**Resource:** [Groups](../resources/Groups.md)
**Download a single group upload by ID**
**Operation ID:** `getApiV4GroupsIdUploadsUploadId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `upload_id` | path | integer | Yes | The ID of a group upload |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 403 | Unauthenticated |
| 404 | Not found |


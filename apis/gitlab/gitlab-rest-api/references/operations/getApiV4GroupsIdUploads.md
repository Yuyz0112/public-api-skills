# GET /api/v4/groups/{id}/uploads

**Resource:** [Groups](../resources/Groups.md)
**Get the list of uploads of a group**
**Operation ID:** `getApiV4GroupsIdUploads`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 403 | Unauthenticated |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesMarkdownUploadAdmin](../schemas/APIEntitiesMarkdownUploadAdmin/APIEntitiesMarkdownUploadAdmin.md)


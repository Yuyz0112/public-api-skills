# GET /api/v4/projects/{id}/uploads

**Resource:** [Projects](../resources/Projects.md)
**Get the list of uploads of a project**
**Operation ID:** `getApiV4ProjectsIdUploads`

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


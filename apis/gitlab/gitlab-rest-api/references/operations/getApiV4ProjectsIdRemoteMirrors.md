# GET /api/v4/projects/{id}/remote_mirrors

**Resource:** [Remote mirrors](../resources/Remote-mirrors.md)
**List the project's remote mirrors**
**Operation ID:** `getApiV4ProjectsIdRemoteMirrors`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesRemoteMirror](../schemas/APIEntitiesRemoteMirror/APIEntitiesRemoteMirror.md)


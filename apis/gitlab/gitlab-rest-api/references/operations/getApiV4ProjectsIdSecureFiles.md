# GET /api/v4/projects/{id}/secure_files

**Resource:** [Secure files](../resources/Secure-files.md)
**Get list of secure files in a project**
**Operation ID:** `getApiV4ProjectsIdSecureFiles`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project owned by the
        authenticated user |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesCiSecureFile](../schemas/APIEntitiesCiSecureFile/APIEntitiesCiSecureFile.md)


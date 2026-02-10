# GET /api/v4/projects/{id}/secure_files/{secure_file_id}

**Resource:** [Secure files](../resources/Secure-files.md)
**Get the details of a specific secure file in a project**
**Operation ID:** `getApiV4ProjectsIdSecureFilesSecureFileId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project owned by the
        authenticated user |
| `secure_file_id` | path | integer | Yes | The ID of a secure file |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | 404 Not found |

**Success Response Schema:**

[APIEntitiesCiSecureFile](../schemas/APIEntitiesCiSecureFile/APIEntitiesCiSecureFile.md)


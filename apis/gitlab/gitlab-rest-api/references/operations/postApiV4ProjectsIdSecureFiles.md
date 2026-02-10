# POST /api/v4/projects/{id}/secure_files

**Resource:** [Secure files](../resources/Secure-files.md)
**Create a secure file**
**Operation ID:** `postApiV4ProjectsIdSecureFiles`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project owned by the
        authenticated user |

## Request Body

**Required:** Yes

**Content Types:** `multipart/form-data`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | 400 Bad Request |

**Success Response Schema:**

[APIEntitiesCiSecureFile](../schemas/APIEntitiesCiSecureFile/APIEntitiesCiSecureFile.md)


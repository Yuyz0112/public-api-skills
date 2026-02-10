# GET /api/v4/projects/{id}/secure_files/{secure_file_id}/download

**Resource:** [Secure files](../resources/Secure-files.md)
**Download secure file**
**Operation ID:** `getApiV4ProjectsIdSecureFilesSecureFileIdDownload`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project owned by the
        authenticated user |
| `secure_file_id` | path | integer | Yes | The ID of a secure file |

## Responses

| Status | Description |
|--------|-------------|
| 404 | 404 Not found |


# GET /api/v4/projects/{id}/repository/archive

**Resource:** [Repositories](../resources/Repositories.md)
**Get an archive of the repository**
**Operation ID:** `getApiV4ProjectsIdRepositoryArchive`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `sha` | query | string | No | The commit sha of the archive to be downloaded |
| `format` | query | string | No | The archive format |
| `path` | query | string | No | Subfolder of the repository to be downloaded |
| `include_lfs_blobs` | query | boolean | No | Used to exclude LFS objects from archive |
| `exclude_paths` | query | any | No | Comma-separated list of paths to exclude from the archive |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |


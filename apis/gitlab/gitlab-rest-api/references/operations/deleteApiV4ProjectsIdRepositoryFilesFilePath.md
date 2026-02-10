# DELETE /api/v4/projects/{id}/repository/files/{file_path}

**Resource:** [Files](../resources/Files.md)
**Delete an existing file in repository**
**Operation ID:** `deleteApiV4ProjectsIdRepositoryFilesFilePath`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The project ID |
| `file_path` | path | string | Yes | The URL-encoded path to the file. |
| `branch` | query | string | Yes | Name of the branch to commit into. To create a new branch, also provide `start_branch`. |
| `commit_message` | query | string | Yes | Commit message |
| `start_branch` | query | string | No | Name of the branch to start the new commit from |
| `author_email` | query | string | No | The email of the author |
| `author_name` | query | string | No | The name of the author |
| `last_commit_id` | query | string | No | Last known file commit id |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |


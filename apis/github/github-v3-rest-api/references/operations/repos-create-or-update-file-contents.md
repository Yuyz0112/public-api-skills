# PUT /repos/{owner}/{repo}/contents/{path}

**Resource:** [repos](../resources/repos.md)
**Create or update file contents**
**Operation ID:** `repos/create-or-update-file-contents`

Creates a new file or replaces an existing file in a repository.

> [!NOTE]
> If you use this endpoint and the "[Delete a file](https://docs.github.com/rest/repos/contents/#delete-a-file)" endpoint in parallel, the concurrent requests will conflict and you will receive errors. You must use these endpoints serially instead.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint. The `workflow` scope is also required in order to modify files in the `.github/workflows` directory.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `path` | path | string | Yes | path parameter |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 201 | Response |
| 404 | (reference) |
| 409 | Conflict |
| 422 | (reference) |

**Success Response Schema:**

[file-commit](../schemas/file-commit/file-commit.md)


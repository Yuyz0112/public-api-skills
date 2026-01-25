# DELETE /repos/{owner}/{repo}/contents/{path}

**Resource:** [repos](../resources/repos.md)
**Delete a file**
**Operation ID:** `repos/delete-file`

Deletes a file in a repository.

You can provide an additional `committer` parameter, which is an object containing information about the committer. Or, you can provide an `author` parameter, which is an object containing information about the author.

The `author` section is optional and is filled in with the `committer` information if omitted. If the `committer` information is omitted, the authenticated user's information is used.

You must provide values for both `name` and `email`, whether you choose to use `author` or `committer`. Otherwise, you'll receive a `422` status code.

> [!NOTE]
> If you use this endpoint and the "[Create or update file contents](https://docs.github.com/rest/repos/contents/#create-or-update-file-contents)" endpoint in parallel, the concurrent requests will conflict and you will receive errors. You must use these endpoints serially instead.

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
| 404 | (reference) |
| 409 | (reference) |
| 422 | (reference) |
| 503 | (reference) |

**Success Response Schema:**

[file-commit](../schemas/file-commit/file-commit.md)


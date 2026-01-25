# GET /repos/{owner}/{repo}/git/ref/{ref}

**Resource:** [git](../resources/git.md)
**Get a reference**
**Operation ID:** `git/get-ref`

Returns a single reference from your Git database. The `:ref` in the URL must be formatted as `heads/<branch name>` for branches and `tags/<tag name>` for tags. If the `:ref` doesn't match an existing ref, a `404` is returned.

> [!NOTE]
> You need to explicitly [request a pull request](https://docs.github.com/rest/pulls/pulls#get-a-pull-request) to trigger a test merge commit, which checks the mergeability of pull requests. For more information, see "[Checking mergeability of pull requests](https://docs.github.com/rest/guides/getting-started-with-the-git-database-api#checking-mergeability-of-pull-requests)".

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |
| 409 | (reference) |

**Success Response Schema:**

[git-ref](../schemas/git-ref/git-ref.md)


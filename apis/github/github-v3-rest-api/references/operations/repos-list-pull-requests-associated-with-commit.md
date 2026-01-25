# GET /repos/{owner}/{repo}/commits/{commit_sha}/pulls

**Resource:** [repos](../resources/repos.md)
**List pull requests associated with a commit**
**Operation ID:** `repos/list-pull-requests-associated-with-commit`

Lists the merged pull request that introduced the commit to the repository. If the commit is not present in the default branch, it will return merged and open pull requests associated with the commit.

To list the open or merged pull requests associated with a branch, you can set the `commit_sha` parameter to the branch name.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 409 | (reference) |

**Success Response Schema:**

Array of [pull-request-simple](../schemas/pull-request-simple/pull-request-simple.md)


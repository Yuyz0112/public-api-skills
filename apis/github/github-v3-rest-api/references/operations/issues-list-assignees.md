# GET /repos/{owner}/{repo}/assignees

**Resource:** [issues](../resources/issues.md)
**List assignees**
**Operation ID:** `issues/list-assignees`

Lists the [available assignees](https://docs.github.com/articles/assigning-issues-and-pull-requests-to-other-github-users/) for issues in a repository.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |

**Success Response Schema:**

Array of [simple-user](../schemas/simple-user/simple-user.md)


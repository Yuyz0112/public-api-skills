# PUT /repos/{owner}/{repo}/pulls/{pull_number}/update-branch

**Resource:** [pulls](../resources/pulls.md)
**Update a pull request branch**
**Operation ID:** `pulls/update-branch`

Updates the pull request branch with the latest upstream changes by merging HEAD from the base branch into the pull request branch.
Note: If making a request on behalf of a GitHub App you must also have permissions to write the contents of the head repository.

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 202 | Response |
| 403 | (reference) |
| 422 | (reference) |


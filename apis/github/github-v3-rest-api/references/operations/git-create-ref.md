# POST /repos/{owner}/{repo}/git/refs

**Resource:** [git](../resources/git.md)
**Create a reference**
**Operation ID:** `git/create-ref`

Creates a reference for your repository. You are unable to create new references for empty repositories, even if the commit SHA-1 hash used exists. Empty repositories are repositories without branches.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response |
| 409 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

[git-ref](../schemas/git-ref/git-ref.md)


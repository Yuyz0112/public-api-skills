# PATCH /repos/{owner}/{repo}/git/refs/{ref}

**Resource:** [git](../resources/git.md)
**Update a reference**
**Operation ID:** `git/update-ref`

Updates the provided reference to point to a new SHA. For more information, see "[Git References](https://git-scm.com/book/en/v2/Git-Internals-Git-References)" in the Git documentation.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 409 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

[git-ref](../schemas/git-ref/git-ref.md)


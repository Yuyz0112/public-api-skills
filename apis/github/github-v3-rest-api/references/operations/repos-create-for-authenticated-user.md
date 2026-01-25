# POST /user/repos

**Resource:** [repos](../resources/repos.md)
**Create a repository for the authenticated user**
**Operation ID:** `repos/create-for-authenticated-user`

Creates a new repository for the authenticated user.

OAuth app tokens and personal access tokens (classic) need the `public_repo` or `repo` scope to create a public repository, and `repo` scope to create a private repository.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response |
| 304 | (reference) |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

[full-repository](../schemas/full-repository/full-repository.md)


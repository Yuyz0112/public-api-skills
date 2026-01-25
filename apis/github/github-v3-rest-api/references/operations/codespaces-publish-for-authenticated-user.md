# POST /user/codespaces/{codespace_name}/publish

**Resource:** [codespaces](../resources/codespaces.md)
**Create a repository from an unpublished codespace**
**Operation ID:** `codespaces/publish-for-authenticated-user`

Publishes an unpublished codespace, creating a new repository and assigning it to the codespace.

The codespace's token is granted write permissions to the repository, allowing the user to push their changes.

This will fail for a codespace that is already published, meaning it has an associated repository.

OAuth app tokens and personal access tokens (classic) need the `codespace` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

[codespace-with-full-repository](../schemas/codespace-with-full-repository/codespace-with-full-repository.md)


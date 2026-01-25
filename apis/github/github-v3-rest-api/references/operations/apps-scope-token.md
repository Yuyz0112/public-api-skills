# POST /applications/{client_id}/token/scoped

**Resource:** [apps](../resources/apps.md)
**Create a scoped access token**
**Operation ID:** `apps/scope-token`

Use a non-scoped user access token to create a repository-scoped and/or permission-scoped user access token. You can specify
which repositories the token can access and which permissions are granted to the
token.

Invalid tokens will return `404 NOT FOUND`.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

[authorization](../schemas/authorization/authorization.md)


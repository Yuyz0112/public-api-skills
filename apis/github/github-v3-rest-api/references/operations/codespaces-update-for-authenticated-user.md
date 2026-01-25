# PATCH /user/codespaces/{codespace_name}

**Resource:** [codespaces](../resources/codespaces.md)
**Update a codespace for the authenticated user**
**Operation ID:** `codespaces/update-for-authenticated-user`

Updates a codespace owned by the authenticated user. Currently only the codespace's machine type and recent folders can be modified using this endpoint.

If you specify a new machine type it will be applied the next time your codespace is started.

OAuth app tokens and personal access tokens (classic) need the `codespace` scope to use this endpoint.

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[codespace](../schemas/codespace/codespace.md)


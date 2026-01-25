# POST /user/emails

**Resource:** [users](../resources/users.md)
**Add an email address for the authenticated user**
**Operation ID:** `users/add-email-for-authenticated-user`

OAuth app tokens and personal access tokens (classic) need the `user` scope to use this endpoint.

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

Array of [email](../schemas/email/email.md)


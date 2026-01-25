# GET /user/emails

**Resource:** [users](../resources/users.md)
**List email addresses for the authenticated user**
**Operation ID:** `users/list-emails-for-authenticated-user`

Lists all of your email addresses, and specifies which one is visible
to the public.

OAuth app tokens and personal access tokens (classic) need the `user:email` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

Array of [email](../schemas/email/email.md)


# GET /user/public_emails

**Resource:** [users](../resources/users.md)
**List public email addresses for the authenticated user**
**Operation ID:** `users/list-public-emails-for-authenticated-user`

Lists your publicly visible email address, which you can set with the
[Set primary email visibility for the authenticated user](https://docs.github.com/rest/users/emails#set-primary-email-visibility-for-the-authenticated-user)
endpoint.

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


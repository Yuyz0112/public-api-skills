# PATCH /user/email/visibility

**Resource:** [users](../resources/users.md)
**Set primary email visibility for the authenticated user**
**Operation ID:** `users/set-primary-email-visibility-for-authenticated-user`

Sets the visibility for your primary email addresses.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

Array of [email](../schemas/email/email.md)


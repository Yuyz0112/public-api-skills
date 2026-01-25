# POST /user/social_accounts

**Resource:** [users](../resources/users.md)
**Add social accounts for the authenticated user**
**Operation ID:** `users/add-social-account-for-authenticated-user`

Add one or more social accounts to the authenticated user's profile.

OAuth app tokens and personal access tokens (classic) need the `user` scope to use this endpoint.

## Request Body

**Required:** Yes

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

Array of [social-account](../schemas/social-account/social-account.md)


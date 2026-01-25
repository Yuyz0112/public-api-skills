# DELETE /user/social_accounts

**Resource:** [users](../resources/users.md)
**Delete social accounts for the authenticated user**
**Operation ID:** `users/delete-social-account-for-authenticated-user`

Deletes one or more social accounts from the authenticated user's profile.

OAuth app tokens and personal access tokens (classic) need the `user` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 422 | (reference) |


# GET /user/social_accounts

**Resource:** [users](../resources/users.md)
**List social accounts for the authenticated user**
**Operation ID:** `users/list-social-accounts-for-authenticated-user`

Lists all of your social accounts.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

Array of [social-account](../schemas/social-account/social-account.md)


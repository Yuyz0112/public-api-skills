# Users

Operations related to users.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v4/users` | Get the list of users | [View](../operations/getApiV4Users.md) |
| POST | `/api/v4/users` | Create a user. Available only for admins. | [View](../operations/postApiV4Users.md) |
| GET | `/api/v4/users/{id}` | Get a single user | [View](../operations/getApiV4UsersId.md) |
| PUT | `/api/v4/users/{id}` | Update a user. Available only for admins. | [View](../operations/putApiV4UsersId.md) |
| DELETE | `/api/v4/users/{id}` | Delete a user. Available only for admins. | [View](../operations/deleteApiV4UsersId.md) |
| GET | `/api/v4/users/{user_id}/status` | Get the status of a user | [View](../operations/getApiV4UsersUserIdStatus.md) |
| POST | `/api/v4/users/{id}/follow` | Follow a user | [View](../operations/postApiV4UsersIdFollow.md) |
| POST | `/api/v4/users/{id}/unfollow` | Unfollow a user | [View](../operations/postApiV4UsersIdUnfollow.md) |
| GET | `/api/v4/users/{id}/following` | Get the users who follow a user | [View](../operations/getApiV4UsersIdFollowing.md) |
| GET | `/api/v4/users/{id}/followers` | Get the followers of a user | [View](../operations/getApiV4UsersIdFollowers.md) |
| PATCH | `/api/v4/users/{id}/disable_two_factor` | Disable two factor authentication for a user. Available only for admins | [View](../operations/patchApiV4UsersIdDisableTwoFactor.md) |
| DELETE | `/api/v4/users/{id}/identities/{provider}` | Delete a user's identity. Available only for admins | [View](../operations/deleteApiV4UsersIdIdentitiesProvider.md) |
| GET | `/api/v4/users/{id}/emails` | Get the emails addresses of a specified user. Available only for admins. | [View](../operations/getApiV4UsersIdEmails.md) |
| POST | `/api/v4/users/{id}/emails` | Add an email address to a specified user. Available only for admins. | [View](../operations/postApiV4UsersIdEmails.md) |
| DELETE | `/api/v4/users/{id}/emails/{email_id}` | Delete an email address of a specified user. Available only for admins. | [View](../operations/deleteApiV4UsersIdEmailsEmailId.md) |
| POST | `/api/v4/users/{id}/activate` | Activate a deactivated user. Available only for admins. | [View](../operations/postApiV4UsersIdActivate.md) |
| POST | `/api/v4/users/{id}/approve` | Approve a pending user. Available only for admins. | [View](../operations/postApiV4UsersIdApprove.md) |
| POST | `/api/v4/users/{id}/reject` | Reject a pending user. Available only for admins. | [View](../operations/postApiV4UsersIdReject.md) |
| POST | `/api/v4/users/{id}/deactivate` | Deactivate an active user. Available only for admins. | [View](../operations/postApiV4UsersIdDeactivate.md) |
| POST | `/api/v4/users/{id}/block` | Block a user. Available only for admins. | [View](../operations/postApiV4UsersIdBlock.md) |
| POST | `/api/v4/users/{id}/unblock` | Unblock a user. Available only for admins. | [View](../operations/postApiV4UsersIdUnblock.md) |
| POST | `/api/v4/users/{id}/ban` | Ban a user. Available only for admins. | [View](../operations/postApiV4UsersIdBan.md) |
| POST | `/api/v4/users/{id}/unban` | Unban a user. Available only for admins. | [View](../operations/postApiV4UsersIdUnban.md) |
| GET | `/api/v4/users/{user_id}/memberships` | Get memberships | [View](../operations/getApiV4UsersUserIdMemberships.md) |
| GET | `/api/v4/users/{id}/associations_count` | Returns a list of a specified user's count of projects, groups, issues and merge requests. | [View](../operations/getApiV4UsersIdAssociationsCount.md) |
| GET | `/api/v4/user` | Get the currently authenticated user | [View](../operations/getApiV4User.md) |
| GET | `/api/v4/user/emails` | Get the currently authenticated user's email addresses | [View](../operations/getApiV4UserEmails.md) |
| POST | `/api/v4/user/emails` | Add new email address to the currently authenticated user | [View](../operations/postApiV4UserEmails.md) |
| PUT | `/api/v4/user/{user_id}/credit_card_validation` | [DEPRECATED] Update a user's credit_card_validation | [View](../operations/putApiV4UserUserIdCreditCardValidation.md) |
| GET | `/api/v4/user/preferences` | Get the current user's preferences | [View](../operations/getApiV4UserPreferences.md) |
| PUT | `/api/v4/user/preferences` | Update the current user's preferences | [View](../operations/putApiV4UserPreferences.md) |
| GET | `/api/v4/user/emails/{email_id}` | Get a single email address owned by the currently authenticated user | [View](../operations/getApiV4UserEmailsEmailId.md) |
| DELETE | `/api/v4/user/emails/{email_id}` | Delete an email address from the currently authenticated user | [View](../operations/deleteApiV4UserEmailsEmailId.md) |
| GET | `/api/v4/user/activities` | Get a list of user activities | [View](../operations/getApiV4UserActivities.md) |
| GET | `/api/v4/user_counts` | Return the user specific counts | [View](../operations/getApiV4UserCounts.md) |

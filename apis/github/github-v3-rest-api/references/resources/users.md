# users

Interact with and view information about users and also current user.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/user` | Get the authenticated user | [View](../operations/users-get-authenticated.md) |
| PATCH | `/user` | Update the authenticated user | [View](../operations/users-update-authenticated.md) |
| GET | `/user/blocks` | List users blocked by the authenticated user | [View](../operations/users-list-blocked-by-authenticated-user.md) |
| GET | `/user/blocks/{username}` | Check if a user is blocked by the authenticated user | [View](../operations/users-check-blocked.md) |
| PUT | `/user/blocks/{username}` | Block a user | [View](../operations/users-block.md) |
| DELETE | `/user/blocks/{username}` | Unblock a user | [View](../operations/users-unblock.md) |
| PATCH | `/user/email/visibility` | Set primary email visibility for the authenticated user | [View](../operations/users-set-primary-email-visibility-for-authenticated-user.md) |
| GET | `/user/emails` | List email addresses for the authenticated user | [View](../operations/users-list-emails-for-authenticated-user.md) |
| POST | `/user/emails` | Add an email address for the authenticated user | [View](../operations/users-add-email-for-authenticated-user.md) |
| DELETE | `/user/emails` | Delete an email address for the authenticated user | [View](../operations/users-delete-email-for-authenticated-user.md) |
| GET | `/user/followers` | List followers of the authenticated user | [View](../operations/users-list-followers-for-authenticated-user.md) |
| GET | `/user/following` | List the people the authenticated user follows | [View](../operations/users-list-followed-by-authenticated-user.md) |
| GET | `/user/following/{username}` | Check if a person is followed by the authenticated user | [View](../operations/users-check-person-is-followed-by-authenticated.md) |
| PUT | `/user/following/{username}` | Follow a user | [View](../operations/users-follow.md) |
| DELETE | `/user/following/{username}` | Unfollow a user | [View](../operations/users-unfollow.md) |
| GET | `/user/gpg_keys` | List GPG keys for the authenticated user | [View](../operations/users-list-gpg-keys-for-authenticated-user.md) |
| POST | `/user/gpg_keys` | Create a GPG key for the authenticated user | [View](../operations/users-create-gpg-key-for-authenticated-user.md) |
| GET | `/user/gpg_keys/{gpg_key_id}` | Get a GPG key for the authenticated user | [View](../operations/users-get-gpg-key-for-authenticated-user.md) |
| DELETE | `/user/gpg_keys/{gpg_key_id}` | Delete a GPG key for the authenticated user | [View](../operations/users-delete-gpg-key-for-authenticated-user.md) |
| GET | `/user/keys` | List public SSH keys for the authenticated user | [View](../operations/users-list-public-ssh-keys-for-authenticated-user.md) |
| POST | `/user/keys` | Create a public SSH key for the authenticated user | [View](../operations/users-create-public-ssh-key-for-authenticated-user.md) |
| GET | `/user/keys/{key_id}` | Get a public SSH key for the authenticated user | [View](../operations/users-get-public-ssh-key-for-authenticated-user.md) |
| DELETE | `/user/keys/{key_id}` | Delete a public SSH key for the authenticated user | [View](../operations/users-delete-public-ssh-key-for-authenticated-user.md) |
| GET | `/user/public_emails` | List public email addresses for the authenticated user | [View](../operations/users-list-public-emails-for-authenticated-user.md) |
| GET | `/user/social_accounts` | List social accounts for the authenticated user | [View](../operations/users-list-social-accounts-for-authenticated-user.md) |
| POST | `/user/social_accounts` | Add social accounts for the authenticated user | [View](../operations/users-add-social-account-for-authenticated-user.md) |
| DELETE | `/user/social_accounts` | Delete social accounts for the authenticated user | [View](../operations/users-delete-social-account-for-authenticated-user.md) |
| GET | `/user/ssh_signing_keys` | List SSH signing keys for the authenticated user | [View](../operations/users-list-ssh-signing-keys-for-authenticated-user.md) |
| POST | `/user/ssh_signing_keys` | Create a SSH signing key for the authenticated user | [View](../operations/users-create-ssh-signing-key-for-authenticated-user.md) |
| GET | `/user/ssh_signing_keys/{ssh_signing_key_id}` | Get an SSH signing key for the authenticated user | [View](../operations/users-get-ssh-signing-key-for-authenticated-user.md) |
| DELETE | `/user/ssh_signing_keys/{ssh_signing_key_id}` | Delete an SSH signing key for the authenticated user | [View](../operations/users-delete-ssh-signing-key-for-authenticated-user.md) |
| GET | `/user/{account_id}` | Get a user using their ID | [View](../operations/users-get-by-id.md) |
| GET | `/users` | List users | [View](../operations/users-list.md) |
| GET | `/users/{username}` | Get a user | [View](../operations/users-get-by-username.md) |
| POST | `/users/{username}/attestations/bulk-list` | List attestations by bulk subject digests | [View](../operations/users-list-attestations-bulk.md) |
| POST | `/users/{username}/attestations/delete-request` | Delete attestations in bulk | [View](../operations/users-delete-attestations-bulk.md) |
| DELETE | `/users/{username}/attestations/digest/{subject_digest}` | Delete attestations by subject digest | [View](../operations/users-delete-attestations-by-subject-digest.md) |
| DELETE | `/users/{username}/attestations/{attestation_id}` | Delete attestations by ID | [View](../operations/users-delete-attestations-by-id.md) |
| GET | `/users/{username}/attestations/{subject_digest}` | List attestations | [View](../operations/users-list-attestations.md) |
| GET | `/users/{username}/followers` | List followers of a user | [View](../operations/users-list-followers-for-user.md) |
| GET | `/users/{username}/following` | List the people a user follows | [View](../operations/users-list-following-for-user.md) |
| GET | `/users/{username}/following/{target_user}` | Check if a user follows another user | [View](../operations/users-check-following-for-user.md) |
| GET | `/users/{username}/gpg_keys` | List GPG keys for a user | [View](../operations/users-list-gpg-keys-for-user.md) |
| GET | `/users/{username}/hovercard` | Get contextual information for a user | [View](../operations/users-get-context-for-user.md) |
| GET | `/users/{username}/keys` | List public keys for a user | [View](../operations/users-list-public-keys-for-user.md) |
| GET | `/users/{username}/social_accounts` | List social accounts for a user | [View](../operations/users-list-social-accounts-for-user.md) |
| GET | `/users/{username}/ssh_signing_keys` | List SSH signing keys for a user | [View](../operations/users-list-ssh-signing-keys-for-user.md) |

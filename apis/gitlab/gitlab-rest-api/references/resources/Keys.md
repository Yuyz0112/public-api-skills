# Keys

Operations related to keys.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v4/users/{user_id}/keys` | Get the SSH keys of a specified user. | [View](../operations/getApiV4UsersUserIdKeys.md) |
| POST | `/api/v4/users/{user_id}/keys` | Add an SSH key to a specified user. Available only for admins. | [View](../operations/postApiV4UsersUserIdKeys.md) |
| GET | `/api/v4/users/{id}/keys/{key_id}` | Get a SSH key of a specified user. | [View](../operations/getApiV4UsersIdKeysKeyId.md) |
| DELETE | `/api/v4/users/{id}/keys/{key_id}` | Delete an existing SSH key from a specified user. Available only for admins. | [View](../operations/deleteApiV4UsersIdKeysKeyId.md) |
| GET | `/api/v4/users/{id}/gpg_keys` | Get the GPG keys of a specified user. | [View](../operations/getApiV4UsersIdGpgKeys.md) |
| POST | `/api/v4/users/{id}/gpg_keys` | Add a GPG key to a specified user. Available only for admins. | [View](../operations/postApiV4UsersIdGpgKeys.md) |
| GET | `/api/v4/users/{id}/gpg_keys/{key_id}` | Get a specific GPG key for a given user. | [View](../operations/getApiV4UsersIdGpgKeysKeyId.md) |
| DELETE | `/api/v4/users/{id}/gpg_keys/{key_id}` | Delete an existing GPG key from a specified user. Available only for admins. | [View](../operations/deleteApiV4UsersIdGpgKeysKeyId.md) |
| POST | `/api/v4/users/{id}/gpg_keys/{key_id}/revoke` | Revokes an existing GPG key from a specified user. Available only for admins. | [View](../operations/postApiV4UsersIdGpgKeysKeyIdRevoke.md) |
| GET | `/api/v4/user/keys` | Get the currently authenticated user's SSH keys | [View](../operations/getApiV4UserKeys.md) |
| POST | `/api/v4/user/keys` | Add a new SSH key to the currently authenticated user | [View](../operations/postApiV4UserKeys.md) |
| GET | `/api/v4/user/keys/{key_id}` | Get a single key owned by currently authenticated user | [View](../operations/getApiV4UserKeysKeyId.md) |
| DELETE | `/api/v4/user/keys/{key_id}` | Delete an SSH key from the currently authenticated user | [View](../operations/deleteApiV4UserKeysKeyId.md) |
| GET | `/api/v4/user/gpg_keys` | Get the currently authenticated user's GPG keys | [View](../operations/getApiV4UserGpgKeys.md) |
| POST | `/api/v4/user/gpg_keys` | Add a new GPG key to the currently authenticated user | [View](../operations/postApiV4UserGpgKeys.md) |
| GET | `/api/v4/user/gpg_keys/{key_id}` | Get a single GPG key owned by currently authenticated user | [View](../operations/getApiV4UserGpgKeysKeyId.md) |
| DELETE | `/api/v4/user/gpg_keys/{key_id}` | Delete a GPG key from the currently authenticated user | [View](../operations/deleteApiV4UserGpgKeysKeyId.md) |
| POST | `/api/v4/user/gpg_keys/{key_id}/revoke` | Revoke a GPG key owned by currently authenticated user | [View](../operations/postApiV4UserGpgKeysKeyIdRevoke.md) |
| GET | `/api/v4/keys/{id}` | Get single ssh key by id. Only available to admin users | [View](../operations/getApiV4KeysId.md) |
| GET | `/api/v4/keys` | Get user by fingerprint of SSH key | [View](../operations/getApiV4Keys.md) |
| GET | `/api/v4/groups/{id}/ssh_certificates` | Get a list of ssh certificates created for a group. | [View](../operations/getApiV4GroupsIdSshCertificates.md) |
| POST | `/api/v4/groups/{id}/ssh_certificates` | Create a ssh certificate for a group. | [View](../operations/postApiV4GroupsIdSshCertificates.md) |
| DELETE | `/api/v4/groups/{id}/ssh_certificates/{ssh_certificates_id}` | Removes an ssh certificate from a group. | [View](../operations/deleteApiV4GroupsIdSshCertificatesSshCertificatesId.md) |

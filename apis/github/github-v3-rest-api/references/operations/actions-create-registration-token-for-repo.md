# POST /repos/{owner}/{repo}/actions/runners/registration-token

**Resource:** [actions](../resources/actions.md)
**Create a registration token for a repository**
**Operation ID:** `actions/create-registration-token-for-repo`

Returns a token that you can pass to the `config` script. The token expires after one hour.

For example, you can replace `TOKEN` in the following example with the registration token provided by this endpoint to configure your self-hosted runner:

```
./config.sh --url https://github.com/octo-org --token TOKEN
```

Authenticated users must have admin access to the repository to use this endpoint.

OAuth tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response |

**Success Response Schema:**

[authentication-token](../schemas/authentication-token/authentication-token.md)


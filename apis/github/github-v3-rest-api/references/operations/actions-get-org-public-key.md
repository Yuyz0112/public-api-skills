# GET /orgs/{org}/actions/secrets/public-key

**Resource:** [actions](../resources/actions.md)
**Get an organization public key**
**Operation ID:** `actions/get-org-public-key`

Gets your public key, which you need to encrypt secrets. You need to
encrypt a secret before you can create or update secrets.

The authenticated user must have collaborator access to a repository to create, update, or read secrets.

OAuth tokens and personal access tokens (classic) need the`admin:org` scope to use this endpoint. If the repository is private, OAuth tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[actions-public-key](../schemas/actions-public-key/actions-public-key.md)


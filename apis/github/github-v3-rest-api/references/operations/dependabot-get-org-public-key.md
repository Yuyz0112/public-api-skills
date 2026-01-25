# GET /orgs/{org}/dependabot/secrets/public-key

**Resource:** [dependabot](../resources/dependabot.md)
**Get an organization public key**
**Operation ID:** `dependabot/get-org-public-key`

Gets your public key, which you need to encrypt secrets. You need to
encrypt a secret before you can create or update secrets.

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[dependabot-public-key](../schemas/dependabot-public-key/dependabot-public-key.md)


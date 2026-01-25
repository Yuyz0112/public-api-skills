# GET /orgs/{org}/private-registries/public-key

**Resource:** [private-registries](../resources/private-registries.md)
**Get private registries public key for an organization**
**Operation ID:** `private-registries/get-org-public-key`


Gets the org public key, which is needed to encrypt private registry secrets. You need to encrypt a secret before you can create or update secrets.

OAuth tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |


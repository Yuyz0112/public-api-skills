# POST /orgs/{org}/code-security/configurations/{configuration_id}/attach

**Resource:** [code-security](../resources/code-security.md)
**Attach a configuration to repositories**
**Operation ID:** `code-security/attach-configuration`

Attach a code security configuration to a set of repositories. If the repositories specified are already attached to a configuration, they will be re-attached to the provided configuration.

If insufficient GHAS licenses are available to attach the configuration to a repository, only free features will be enabled.

The authenticated user must be an administrator or security manager for the organization to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `write:org` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 202 | (reference) |


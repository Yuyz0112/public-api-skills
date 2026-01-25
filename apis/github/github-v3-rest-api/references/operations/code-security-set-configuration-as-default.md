# PUT /orgs/{org}/code-security/configurations/{configuration_id}/defaults

**Resource:** [code-security](../resources/code-security.md)
**Set a code security configuration as a default for an organization**
**Operation ID:** `code-security/set-configuration-as-default`

Sets a code security configuration as a default to be applied to new repositories in your organization.

This configuration will be applied to the matching repository type (all, none, public, private and internal) by default when they are created.

The authenticated user must be an administrator or security manager for the organization to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `write:org` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Default successfully changed. |
| 403 | (reference) |
| 404 | (reference) |


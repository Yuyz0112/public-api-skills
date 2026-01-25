# POST /orgs/{org}/actions/runners/generate-jitconfig

**Resource:** [actions](../resources/actions.md)
**Create configuration for a just-in-time runner for an organization**
**Operation ID:** `actions/generate-runner-jitconfig-for-org`

Generates a configuration that can be passed to the runner application at startup.

The authenticated user must have admin access to the organization.

OAuth tokens and personal access tokens (classic) need the`admin:org` scope to use this endpoint. If the repository is private, OAuth tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 422 | (reference) |


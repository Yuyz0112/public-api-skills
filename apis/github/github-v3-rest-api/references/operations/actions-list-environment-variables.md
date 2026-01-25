# GET /repos/{owner}/{repo}/environments/{environment_name}/variables

**Resource:** [actions](../resources/actions.md)
**List environment variables**
**Operation ID:** `actions/list-environment-variables`

Lists all environment variables.

Authenticated users must have collaborator access to a repository to create, update, or read variables.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |


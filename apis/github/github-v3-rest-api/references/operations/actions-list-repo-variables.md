# GET /repos/{owner}/{repo}/actions/variables

**Resource:** [actions](../resources/actions.md)
**List repository variables**
**Operation ID:** `actions/list-repo-variables`

Lists all repository variables.

Authenticated users must have collaborator access to a repository to create, update, or read variables.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |


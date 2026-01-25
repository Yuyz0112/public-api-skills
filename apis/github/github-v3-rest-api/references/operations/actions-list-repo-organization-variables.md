# GET /repos/{owner}/{repo}/actions/organization-variables

**Resource:** [actions](../resources/actions.md)
**List repository organization variables**
**Operation ID:** `actions/list-repo-organization-variables`

Lists all organization variables shared with a repository.

Authenticated users must have collaborator access to a repository to create, update, or read variables.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |


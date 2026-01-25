# GET /orgs/{org}/actions/variables

**Resource:** [actions](../resources/actions.md)
**List organization variables**
**Operation ID:** `actions/list-org-variables`

Lists all organization variables.

Authenticated users must have collaborator access to a repository to create, update, or read variables.

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint. If the repository is private, the `repo` scope is also required.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |


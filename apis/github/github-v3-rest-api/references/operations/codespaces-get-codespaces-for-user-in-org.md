# GET /orgs/{org}/members/{username}/codespaces

**Resource:** [codespaces](../resources/codespaces.md)
**List codespaces for a user in organization**
**Operation ID:** `codespaces/get-codespaces-for-user-in-org`

Lists the codespaces that a member of an organization has for repositories in that organization.

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |


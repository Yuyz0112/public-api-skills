# GET /orgs/{org}/installations

**Resource:** [orgs](../resources/orgs.md)
**List app installations for an organization**
**Operation ID:** `orgs/list-app-installations`

Lists all GitHub Apps in an organization. The installation count includes
all GitHub Apps installed on repositories in the organization.

The authenticated user must be an organization owner to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `admin:read` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |


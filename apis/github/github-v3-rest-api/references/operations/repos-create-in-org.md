# POST /orgs/{org}/repos

**Resource:** [repos](../resources/repos.md)
**Create an organization repository**
**Operation ID:** `repos/create-in-org`

Creates a new repository in the specified organization. The authenticated user must be a member of the organization.

OAuth app tokens and personal access tokens (classic) need the `public_repo` or `repo` scope to create a public repository, and `repo` scope to create a private repository.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response |
| 403 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

[full-repository](../schemas/full-repository/full-repository.md)

